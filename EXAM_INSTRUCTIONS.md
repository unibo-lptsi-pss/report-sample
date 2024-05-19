# PSS'23/24 - Esame

L’esame per il corso *95648 - PROGETTAZIONE E SVILUPPO DEL SOFTWARE - 9 cfu* cfu consiste in un **progetto** da sviluppare in gruppo, da consegnare e **relazionare**, e poi discutere in un **colloquio orale (di gruppo)**.  

## Aspetti generali

* L’**obiettivo** del progetto/orale è quello di dimostrare la competenza degli argomenti erogati nel corso. 
* Il progetto è di **gruppo** e l’orale corrispondente è da sostenere da tutti i membri del gruppo. L’ideale sarebbe formare gruppi di 3-4 persone,
  che consentono di sperimentare le dinamiche di sviluppo del software collaborativo. Gruppi di 1 o 2 persone possono essere considerate in motivati casi eccezionali.

## Proposta di progetto

* Il progetto va **proposto da un gruppo**.
  La proposta di progetto va effettuata nel [Forum Progetti](https://virtuale.unibo.it/mod/forum/view.php?id=1378493) del [sito del corso](https://virtuale.unibo.it/course/view.php?id=55579)
   e dev’essere comprensiva delle seguenti informazioni
  (si veda il [**post d’esempio** sul Forum Progetti](https://virtuale.unibo.it/mod/forum/discuss.php?d=152002)):
    * Nome del progetto (in minuscolo, senza spazi o caratteri speciali al di fuori di “-”)
    * Componenti del gruppo: nome, cognome, email istituzionale @studio.unibo.it
    * Obiettivo del progetto
        * a livello di dominio, non di "esame" del corso 
    * Requisiti/funzionalità minimi 
    * Requisiti/funzionalità opzionali
        * queste consentono di "aggiungere lavoro" qualora il dimensionamento in termini di requisiti minimi sia risultato troppo ridotto
    * Sfide di progettazione/implementazione prefigurate
        * ad es. aspetti non chiari all'inizio dello sviluppo 
    * Suddivisione del lavoro
        * Si cerchi una suddivisione uniforme ed equilibrata. Evitare allocazioni troppo focalizzate, dove ad es. Tizio fa solo sviluppo di parti di GUI. Si indichi "funzionalità" che quindi catturino vari concern/layer applicativi.
* Una volta proposto il progetto, **attendere la conferma del docente prima di procedere**.

## Sviluppo del progetto

* **Template** di progetto di partenza.
    * Se lo si desidera, si può inizializzare il repository generandolo dal seguente template: <https://github.com/unibo-lptsi-pss/pss-javafx> (si raccomanda di ripulirlo dei file non necessari) 
* Requisiti tecnici del progetto
    * Utilizzo di **git** come strumento di controllo di versione del progetto.
    * Utilizzo di **GitHub** come hosting. Il **nome del repository** sarà così formato: `pss23-24-[Nomeprogetto]-[Cognome1]-[Cognome2]-...`
    * Utilizzo di **Gradle** come build system del progetto.
* Elementi raccomandati per un buon progetto:
    * Buona modellazione del dominio mediante interfacce e classi
    * Interfaccia grafica con JavaFX o Swing – non necessaria, ma può portare ad applicazioni più complesse e carine
    * Applicazione di design pattern (quelli visti nel corso ed eventualmente altri approfonditi autonomamente)
* A proposito della **relazione**. Si faccia riferimento al "template" della relazione fornito ([template della relazione](https://github.com/unibo-lptsi-pss/report-sample)).
    L’obiettivo della relazione è di documentare la vostra soluzione tecnica del progetto, nonché il vostro contributo individuale.
    La relazione dovrebbe semplificare la valutazione da parte del docente, mostrando chiaramente "chi ha fatto cosa",
    quali sono gli elementi salienti della vostra soluzione, e quali elementi visti durante il corso sono stati applicati
    (ad esempio: gerarchie di tipi, collezioni, lambda, stream, binding/osservabili JavaFX, design pattern GOF).  

## Consegna del progetto, prova orale, e valutazione

Modalità di consegna del progetto.

* Il progetto andrà consegnato con una risposta al thread del progetto sul Forum Progetti, fornendo l'**indirizzo URL del repository GitHub del progetto**.
* Nel repository, il file **README.md** conterrà la **relazione** del progetto in sintassi Markdown.
* **Fat JAR** eseguibile dell’applicazione sviluppata. Nel repository dovrà essere presente un file con estensione .jar rappresentante il “deliverable” del progetto.
  Tale file, se scaricato senza alcuna altra risorsa, deve essere eseguibile sui tre principali sistemi operativi (MacOS, Linux, e Windows) assumendo solo un'installazione corretta di Java 17.
    * Eccezioni: Nel caso il progetto sia condiviso con altro corso (es. Lab di Programmazione di Sistemi Mobile), il deliverable potrà essere di altra tipologia (es. APK per Android)

Partecipazione alla **prova orale**. 

* Una volta consegnato il progetto, i docenti provvederanno a una prima fase di controllo e validazione/valutazione.
    * Nel caso la consegna non sia ritenuta valida, potrebbero essere richieste delle integrazioni a quanto sviluppato.
* Terminata questa fase, **i docenti contatteranno il gruppo per concordare una data per la prova orale**.

A proposito della **valutazione** dell'esame. Il voto finale dell'esame dipenderà dai seguenti elementi:

* Qualità interna del progetto sviluppato, in relazione al contributo individuale
* Qualità esterna del progetto sviluppato
* Qualità tecnica del processo adottato (ad es. da quanto deducibile attraverso la history di git)
* Qualità tecnica della relazione del progetto
* Padronanza dei contenuti del corso dimostrata durante l'orale

## Altre questioni

A proposito delle copiature. 

* Premessa: prendere spunto da codice e soluzioni scritti da altri può essere positivo, in quanto prevede la capacità di analizzare una soluzione e di adattarla all’interno del proprio progetto.
  Non c’è nessun problema a farlo, ma chiediamo di indicare nella relazione i progetti/guide/blog/etc. da cui si è preso spunto. 
* Non lo permettiamo, ma possiamo immaginare che possa esserci la tentazione di **"copiare" parti sostanziali di progetti software Java sviluppati da altri**.
  La pratica di partire da un progetto esistente (non vuoto/template), rimuovere parti, e modificarle è una pratica inopportuna. Ci raccomandiamo assolutamente di **non farlo**.
  I progetti che consegnate verranno processati da **strumenti automatici antiplagio** che possono individuare parti copiate da altri progetti su GitHub o pezzi di codice sul web.
* L'individuazione di **plagi/copiature** in un esame universitario è un fatto **grave** che può avere serie ripercussioni sulla vostra carriera. Si veda l’Articolo 25 del [Codice Etico di Ateneo](https://normateneo.unibo.it/codice_etico.html). 
* Durante l’orale, è possibile che vengano chieste delucidazioni relativamente ad alcune soluzioni proposte.

## Domande Frequenti

* *"A quanto ammonta l'impegno individuale stimato da dedicare al progetto?"*. Circa 60-75 ore (poco meno di 2 settimane piene di lavoro). Calcolo: 1 CFU corrisponde a 25 ore di lavoro. Per 9 CFU sono 225 ore. Abbiamo 100 ore di didattica frontale (aula e lab). Da queste scorporiamo altre 50-60 ore di studio autonomo a casa. Le risultanti sono quelle da dedicare al progetto. Ovviamente è solo una stima: in base ad ambizioni, impegni, continuità, inefficienze varie, il computo può variare. 
* *"Posso utilizzare delle librerie esterne?"* Sì: l'utilizzo di librerie esterne è valutato positivamente,
  in quanto prevede la capacità di studiare autonomamente API non trattate durante il corso, facendo leva sulle nozioni apprese. Inoltre, librerie esterne possono semplificare alcuni task del progetto.
* *"Posso utilizzare un framework?"* No: l'utilizzo di un framework potrebbe vincolare eccessivamente l'architettura dell'applicazione, e quindi risparmiarvi questioni di design che invece sono oggetto di valutazione.
* *"Non ho idea di quale progetto sviluppare."* Varie tipologie di progetti possono essere considerati. Seguono alcuni esempi:
    * Un semplice editor di testo. Questo progetto prevede l’utilizzo di una GUI per caricare, manipolare, e salvare documenti testuali (testo puro o formattato).
    * Un’applicazione “gestionale”. Questo tipo di applicazione prevede una interfaccia grafica per l’inserimento, il caricamento, il salvataggio, e la modifica di dati di varia natura. Esempi includono: un’applicazione di gestione delle prenotazioni alberghiere; un’applicazione per la prenotazione di campi sportivi; un’applicazione per la gestione di studenti, corsi, esami in un contesto scolastico.
    * Un visualizzatore di immagini. L’utente può selezionare delle immagini dal proprio filesystem e scegliere diverse viste (1 alla volta, 2 alla volta, griglia..).
    * Una API guidata attraverso command-line o GUI. Ad esempio, una libreria per l’estrazione di notizie dal web.
    * Versioni semplificate di progetti sviluppati nel corso di “Programmazione ad Oggetti” del CdL in Ingegneria e Scienze Informatiche. Si vedano i progetti
    (ATTENZIONE: l’idea è di prendere spunto da essi per decidere COSA fare, non COME – si veda la raccomandazione in alto sul plagio): <https://github.com/unibo-oop-projects>
    * Versioni semplificate di strumenti esistenti – si veda <https://github.com/akullpp/awesome-java> 
* *"Vorrei fare ABC ma non so come fare la cosa XYZ"* Raccomandiamo l’uso del Forum Studenti per porre questioni e domande di natura tecnica.
  I docenti sono anche disponibili per ricevimenti. Attenzione però: si pongano questioni di natura tecnica generali e **non questioni specifiche del progetto** (si veda item successivo).
* *"Nel mio progetto ho fatto XYZ, va bene?"* Si eviti di porre queste domande ai docenti: queste valutazioni sono di fatto oggetto di valutazione in sede di esame.
  Il consiglio è di discuterne coi colleghi, o di estrarre una questione tecnica generale da porre nel Forum Studenti (si veda item precedente).

Per altre domande o dubbi si scriva un post nel Forum Studenti del sito del corso.
