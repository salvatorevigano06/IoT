#CAPITOLO 1

Componenti sistema comunicazione: \* Conversione analogico-digitale e
digitale-analogico \* Codifica e decodifica \* Modulazione e
demodulazione \* Multiplexing e demultiplexing \* Accesso multiplo \*
Canale trasmissione dati

Conversione analogico-digitale (ADC): \* Campionamento: trasforma le
variazioni nel tempo di una grandezza analogica in una grandezza che
varia solo in determinati istanti di tempo (periodo di campionamento) \*
Quantizzazione: limita il numero di valori che la grandezza può assumere
(errore -\> approssimazione valori -\> perdita informazioni) \*
Codifica: ogni intervallo di quantizzazione viene associata una
combinazione di cifre binarie in base alla codifica utilizzata (codice
binario)

Modulazione: tecnica di trasmissione dati che ha lo scopo di associare
un messaggio detto modulante in un altro segnale detto portante,
utilizzato per poter essere adattato per la trasmissione in un canale
trasmissivo. Modulazione: converte la banda occupata dallo spettro del
segnale in una banda detta banda traslata

Multiplexing: tecnica che combina più segnali in un unico, adatto per la
trasmissione su un canale di comunicazione come cavo coassiale o fibra
ottica. Multiplexing: divide il canale di comunicazione in sottocanali
logici, ciascuno dedicato per un solo segnale. Multiplexing: \*
Analogico: \* FDM -\> divisione di frequenza; \* WDM -\> divisione
lunghezza d'onda. \* Digitale: \* TDM: \* Sincrono; \* Asincrono.

Canale: mezzo di comunicazione utilizzato per la trasmissione di
informazioni; può essere: \* Fisico -\> trasmissione segnali tramite
cavi diversi; \* Logico -\> trasmissione segnali tramite un unico tipo
di cavo.

TDM: tecnica trasmissione dati dove un RX ottiene per un determinato
periodo di tempo l'uso esclusivo di un canale (frame = stessa durata)
TDM: linee di input non tutte occupate -\> multiplexer trasmette frame
su più canali per un mittente.

FDM: tecnica trasmissione dati che suddivide un canale in sottocanali,
uno per ciascun mittente. Ogni sottocanale lavora a frequenze diverse,
in modo tale da evitate interferenze. FDM: \* Vantaggi: \* Trasmettere
più segnali contemporaneamente; \* Demodulazione semplice da realizzare;
\* Nessuna sincronizzazione. \* Svantaggi: \* Necessita di una banda
larga.

WDM: utilizzato per aumentare le capacità di una fibra ottica, dove più
segnali vengono trasmessi simultaneamente in un singolo canale di
comunicazione. WDM: \* Vantaggi: \* Aggiornare multiplexer e
demultiplexer facilmente; \* Non è necessario acquistare più fibre
ottiche.

ISO/OSI: standard per reti di calcolatori, composto da sette livelli.
ISO/OSI: \* Fisico: viene regolata la trasmissione dati tra due nodi,
occupandosi della forma e tensione del segnale. \* Collegamento: vengono
formati tutti i pacchetti che verranno instradati lungo la dorsale di
comunicazione. Dati frammentati: header e tail -\> ACK \* Rete: avviene
attività di routing e conversione dati in caso ci siano nodi con
caratteristiche differenti. \* Trasporto: viene determinato tutto ciò
che riguarda la connessione tra due nodi -\> verifica sovraccarico
router. \* Sessione: instaura, mantiene e chiude connessioni tra
applicazioni, e gestisce dialogo e sincronizzazione. \* Presentazione:
avviene trasformazione dati applicazioni in un formato standard,
offrendo servizi di comunicazione comuni -\> crittografia. \*
Applicazione: i protocolli interagiscono direttamente con i programmi e
software che possiedono moduli di comunicazione di rete.

Sistema di comunicazione: \* Fonte: origina un messaggio qualunque \*
Trasduttore: converte la fonte in una forma d'onda elettrica \*
Trasmettitore: modifica il segnale in banda base per rendere efficiente
la trasmissione: \* Pre-enfatizzatore; \* Campionatore; \*
Quantizzatore; \* Codificatore; \* Modulatore. \* Canale: mezzo di
comunicazione utilizzato per trasmettere segnali: \* Wireline: risultano
meno inclini a cadute di connessioni e sono poco influenzate da fattori
locali (pareti, pavimenti). L'affidabilità è più alta e anche la
velocità di connessione, è più sicura ma risulta più scarsa sulla
scalabilità e mobilità. \* Wireless: facilmente scalabili, con
configurazioni semplici e veloci. Subiscono interferenze di segnale,
influendo sulla velocità di trasmissione dati. \* Ricevitore: elabora il
segnale ricevuto dal canale, annullando le modifiche apportate dal
trasmissione. Estrae il messaggio distorto, con possibile segnale di
rumore: \* Demodulatore; \* Decodificatore; \* Filtro; \*
De-enfatizzatore.

Sensore: dispositivo in grado di misurare una grandezza fisica non
elettrica, convertendola in una grandezza di tipo elettrico. Attuatore:
dispositivo in grando di convertire una grandezza elettrica in una
grandezza fisica.

CAPITOLO 2

Antenna: strumento elettronico che permette di trasmettere e ricevere
informazioni; è un conduttore elettrico dove: \* Trasmissione: irradia
energia elettromagnetica nello spazio; \* Ricezione: raccoglie energie
elettromagnetica dallo spazio.

Antenne bidirezionali: un'unica antenna che può svolgere sia
trasmissione che ricezione.

Radiofrequenza: segnale elettrico/onda elettromagnetica ad alta
frequenza che si propaga nello spazio.

Ampiezza: massima variazione di una grandezza analogica in
un'oscillazione periodica.

Fase: frazione di periodo trascorsa rispetto ad un tempo fissato

Frequenza: misura il numero di volte che un segnale di ripete in un
secondo.

Propagazioni RF: \* Onda terrestre o di superficie: Antenne TX e RX sono
vicine al suolo, con differenza di altezza relativamente piccola ed
entrambe le antenne sono polarizzate verticalmente. L'onda si propaga al
suolo, seguendo la curvatura terrestre. \* Onda spaziale diretta:
Antenne TX e RX si trovano ad un'altezza superiore rispetto alla
lunghezza d'onda trasmessa. \* Onda spaziale riflessa dalla ionosfera:
Antenne TX e RX non riescono a comunicare tra di loro in quanto le onde
provengono dalla ionosfera dato il riflesso. \* Onda spaziale riflessa
dai satelliti: Il segnale inviato nello spazio ha un angolo incidente
molto piccolo (nel caso precedente 90° o superiore) ed è indirizzato in
un punto preciso (satellite geostazionario).

ITU: Organismo internazionale delle telecomunicazioni che ha stabilito
in quale frequenza e in quale lunghezza d'onda viene collogato un
dispositivo.

Bandwidth: quantità massima di dati che è possibile inviare in un
percorso di comunicazione (canale) in un secondo.

Decibel: unità di misura utilizzata per esprimere differenze tra due o
più segnali -\> 10log\_10(P1/P2)

Radiatore isotropico: antenna che irradia omogeneamente in tutte le
direzioni.

Diagrammi di radiazione: viene rappresentata l'intensità di campo delle
antenne, che variano con la direzione e con il comportamento: \* Lobo
principale: indica la direzione di massima radiazione; \* Lobo
secondario: limitano la qualità dell'antenna, generando eventuali
interferenze su altri sistemi di radiocomunicazione.

Effetto Joule: viene generata corrente elettrica nelle antenne in
quanto, durante la tramissione e ricezione, vi è la presenza di calore
-\> viene convertita in energia.

Antenna isotropa: irradia in ogni direzione omogeneamente, e ha come
diagramma di ricezione una sfera -\> rappresetazione piana: cerchio.

Guadagno: rapporto tra la potenza dell'antenna isotropa e la potenza
irradiata dall'antenna in esame

ERP: L'Effective Radiated Power indica quanto intenso sia il campo
prodotto nella direzione di massima irradiazione (potenza irradiata
dall'antenna in esame x il Guadagno)

Multipath: l'onda elettromagnetica può seguire più percorsi dal
trasmettitore al ricevitore: \* Fading: forma di distorsione di un
segnale che giunge a destinazione sottoforma di un certo numero di
repliche sfasate nel tempo -\> ogni replica avrà compiuto un percorso
diversa, con una certa lunghezza e con una riflessione differente. \*
Modello di riflessione a due raggi: modello multipath che prevede
perdite di percorso tra antenna TX e antenna RX quando sono in linea di
vista (onda terreste o di superficie).

CAPITOLO 3 e 4

Microprocessore: è un'unità di calcolo centrale, che gestisce le
operazioni aritmetiche (ALU).

Microcontrollore: è un sistema che contiene componenti elettronici come
CPU, RAM, Memorie e porte I/O.

CAPITOLO 5

Modulazione analogica: \* AM: consiste nel variare l'ampiezza dell'onda
portante in radiofrequenza (8-10 KHz). Dato che le frequenze risultano
essere basse e le lunghezze d'onda risultano, invece, molto lunghe, la
gamma del segnale è sicuramente più ampia rispetto a quella della
frequenza modulata. Sono più vulnerabili al rumore; \* FM: consiste nel
variare la frequenza dell'onda portante in radiofrequenza. Il canale ha
una larghezza di banda di circa 200KHz, consentendo di trasmettere
informazioni più fedeli e di qualità superiore.

Modulazione digitale: \* ASK: consiste nel variare l'ampiezza del
segnale portante con il ritmo del segnale modulante. Il modulatore
trasmette la portante senza nessuna variazione quando il segnale è
livello alto, mentre blocca la portante quando il segnale è livello
basso. \* FSK: consiste nel variare la frequenza del segnale portante
con il ritmo del segnale modulante. Questo metodo permette di utilizzare
un ricetrasmettitore relativamente semplice da realizzare e assicura un
alto livello di immunità di disturbi, ma avremo velocità di trasmissione
bassa. \* PSK: consiste nel variare la fase del segnale portante con il
ritmo del segnale modulante. Questo metodo assicura un buo livello di
immunità ai disturbi e consente delle velocità di trasmissioni elevate,
ma richeide un ricetrasmettitore più complesso rispetto al metodo FSK.

Modalità trasmissione simplex: modalità più semplice di comunicazione,
unidirezionale -\> il mittente ha solamente la capacità di inviare dati

Modalità trasmissione half-duplex: modalità di comunicazione
bidirezionale, ma con ritardi. I dati possono viaggiare solo in una
direzione alla volta.

Modalità di trasmissione full-duplex: modalità di comunicazione più
avanzata, dove i dati possono essere inviati e ricevuti da entrambe le
direzioni contemporaneamente.

Tecniche accesso multiplo: \* FDMA: a ciascun utente viene assegnata una
banda o un canale di frequenza univoco e nessun altro può condividere la
stessa banda di frequenza. \* TDMA: viene diviso lo spettro radio in
intervalli di tempo, in ciascuno dei quali un solo utente può
trasmettere o ricevere. \* SDMA: viene controllata l'energia irradiata
per ogni utente nello spazio.

Modulazione OFDM: tecnica di trasmissione dati in parallelo, utilizzando
u certo numero di portanti ortogonali tra loro. Questa tecnica consente
di suddividere una trasmissione in tanti flussi paralleli e ortogonali
con bit-rate molto basso, contrastando effetti deleteri che possono
verificarsi su canali affetti da propagazione per cammini multipli.

Throughput: frequenza con cui vengono trasmetti i dati, definito come la
quantità di dati esportati da un luogo ad un altro in un determinato
periodo.

CAPITOLO 6

Subnetting: tecnica che permette di dividere una rete in sottoreti,
utilizzando la parte di host di un indirizzo IP.

Subnet mask: ricava la rete a cui appartiene un dispositivo partendo dal
suo indirizzo IP, e consente di stabilire quali risorse sono da
considerarsi locali e quali invece globali. E' formato da 32 bit o 4
byte (ciascun gruppi formato da 8 bit, separato con un punto).

ARP: protocollo di livello rete che ci consente di ottenere l'indirizzo
MAC di una stazione di cui è noto l'indirizzo IP. Un pacchetto IP può
arrivare a destinazione solo se è noto l'indirizzo MAC della stazione
destinataria.

ARP Cache: tabella dove vengono memorizzare le corrispondenze tra
indirizzi IP e indirizzi MAC. Può contenere sia voci dinamiche (vengono
aggiunte/rimosse automaticamente), sia voci statiche (restano nella
cache finché il sistema non viene riavviato).

Procedura ARP: \* Stazione A cerca nella ARP cache l'indirizzo IP della
stazione B: \* Trovato? Ottengono indirizzo MAC, lo salvo nella cache e
comincio la trasmissione; \* Non trovato? Invio pacchetto broadcast con
indirizzo MAC e IP di A e indirizzo IP di B; \* Stazione B riceve
pacchetto broadcast, e invia un pacchetto di risposta con il proprio
indirizzo MAC: \* Stazione A riceve pacchetto risposta e memorizza
indirizzo MAC nella ARP Cache, per poi iniziare la trasmissione.

TTL: indica per quanto tempo un record rimane memorizzato nella cache di
un server DNS.

Indirizzo IP: indirizzo univoco che identifica un dispositivo su
Internet o in una rete locale.

Broadcast: indirizzo IP utilizzato per indirizzare tutti i sistemi di
una rete, anziché ai singoli host.

Indirizzo MAC: indirizzo che permette a due dispositivi connessi
fisicamente tra loro di scambiare dati che, al tempo stesso, vengono
ignorati da altri dispositivi che condividono la stessa connessione
fisica.

BSS: topologia di rete che consente a tutti i dispositivi wireless di
comunicare tra loro attraverso un mezzo comune (AP). Ogni BSS ha il suo
BSSID, indirizzo MAC di AP associato a BSS.

BSS: \* Vantaggi: \* Rete a piccola portata -\> più sicura; \*
Dispositivi comunicano facilmente tra loro; \* AP gestisce tutte le
stazioni all'interno del BSS e rende la rete più portatile e gestibile.
\* Svantaggi: \* Contiene un solo AP -\> niente mobilità; \* Fornisce
comunicazioni wireless a corto raggio; \* Ogni stazione condivide o
comunica attraverso lo stesso mezzo.

Passive scanning: metodo di rilevamento delle vulnerabilità, che si basa
sulle informazioni raccolte dai dati di rete acquisiti da una stazione
di destinazione senza itnerazione diretta. Passive scanning: si basa
sullo sniffing dei pacchetti Passive scanning: \* Vantaggi: \* Intruso:
non lascia tracce che potrebbero avvisare utenti o amministratori. \*
Amministratore: non causa comportamenti indesiderati sul computer di
destinazione. \* Svantaggi: \* Forti limitazioni ha livello di
comunicazione; \* Non è completo nel dettagio.

Active scanning: come il passive scanning, ma più costoso e meno
affidabile (sia in tempi di attività che affidabilità del sistema).

Chiave WEP: chiave di rete utilizzata per l'autenticazione in un
handshake domanda-risposta in quattro fasi: \* Client invia richiesta
all'AP; \* AP risponde con CTC (clear text challenge); \* Client
crittografa il CTC utilizzando la chiave WEp e invia un'altra richiesta
di autenticazioen; \* AP decrifra la chiave: \* Corrisponde? Accesso
confermato; \* Non corrisponde? Accesso negato.

Chiave WEP: poco sicura e molto facile da manomettere, dato che è
possibile derivare facilmente il keystream.

RC4: nodo cifratore a flusso che, a partire da una chiave, genera una
sequenza pseudocasuale (keystream) utilizzata per cifrare e decifrare
(XOR) un flusso di dati.

RTS: prenotazione del canale da parte del protocollo a livello di rete,
dove il pacchetto RTS viene inviato dal terminale direttamente all'AP di
destinazione che, a sua volta, risponderà in broadcast con un messaggio
di CTS -\> procedura che migliora prestazioni e risolve il problema del
terminale nascosto (necessitano i beacon per rilevare le reti)

DCF: modalità di trasmissione dati per reti ad-hoc: Supponiamo che B
abbia necessità di trasmettere ad A. Il terminale B quando trova il
canale libero manda un pacchetto RTS. A riceve l'RTS, lo interpreta come
una richiesta di connessione fatta da B e risponde con un CTS. Questo
messaggio per B viene interpretato come una conferma di accesso, mentre
per gli altri nodi, che hanno visto il CTS, significa che si sta
instaurando una comunicazione tra A e B e quindi evitano di trasmettere
pacchetti. I terminali che percepiscono i pacchetti RTS e CTS settano un
NAV (Network Allocation Vector), un contatore interno che viene
decrementato nel tempo. Il valore al quale viene settato il NAV è quello
presente nei pacchetti RTS e CTS e rappresenta sostanzialmente la durata
della trasmissione tra il terminale B e il terminale A. Il terminale B,
dunque, effettua la trasmissione al terminale A che risponde, se riceve
il messaggio in maniera corretta, con un ACK (Acknowledge). Questo
pacchetto per il terminale B ha valore di corretta ricezione del
messaggio, mentre per gli altri nodi della rete indica che il canale è
libero ed è terminata la comunicazione tra B ed A. Dato che le
trasmissioni radio hanno il difetto di non essere buoni canali di
trasmissione, in quanto il rumore ambientale incide fortemente sulla
qualità del canale, i messaggi vengono frammentati in frame e numerati
in maniera progressiva.

PCF: modalità di trasmissione dati per reti wireless: Questo metodo di
trasmissione dati si basa sul polling, ovvero sull'interrogazione a
turno dei client connessi all'Access Point. Quest'ultimo, dunque, regola
l'accesso al mezzo trasmissivo in maniera molto rigida; Avremo che un
client non può inviare dati se non è stato autorizzato precedentemente
dall'Access Point e non può ricevere dati in ingresso se non è stato
selezionato direttamente dall'Access Point. Principalmente questo metodo
è orientato verso le applicazioni in tempo reale (video, voce,
streaming) che necessitano di una gestione dei tempi delle trasmissioni
di dati con cadenza regolare. Si tratta, in sostanza, di una modalità
con accesso ordinato al canale che viene comandato dall'Access Point.

CAPITOLO 8

Metodo GET: i dati che devono essere inviati al servere sono scritti
direttamente all'interno dell'URL. Metodo GET: \* Vantaggi: \* I
parametri URL possono essere salvati insieme all'indirizzo del sito web.
\* Svantaggi: \* Assenza di protezione dei dati; \* Capacità limitata.

Meotodo POST: scrive i parametri URL nella richiesta HTTP. \* Vantaggi:
\* Più affidabile e sicuro; \* Maggiore flessibilità rispetto al metodo
GET. \* Svantaggi: \* I dati inseriti in un modulo vanno inseriti e
trasmessi ogni volta.

CAPITOLO 9

API: insieme di definizioni e protocolli dove vengono utilizzati per
software applicativi (si basa sull'architettura Client-Server).

REST: stile architetturale che fornisce degli standard a diversi sistemi
informatici sul Web

RESTful: REST ma con API

MQTT: protocollo trasmissione dati TCP/IP basato su un modello di
pubblicazione e sottoscrizione tramite message broker MQTT: Mittente
invia messaggio di un argomento, e i destinatari si iscrivono agli
argomenti; i broker provvedono alla trasmissione dei messaggi tra le due
parti.

QoS: Quality Of Service, una delle funzionalità di MQTT -\> garantisce
accuratezza durante la consegna dei messaggi. QoS: \* Livello 0 (Al
massimo una volta): Massime prestazioni con il minor sforzo -\> nessuna
garanzia di consegna; \* Livello 1 (Almeno una volta): Il mittente
mantiene in memoria il messaggio finché non riceve un ACK da parte del
destinatario; \* Livello 2 (Esattamente una volta): Molto lenta ma molto
affidabile (doppio rimbalzo tra mittente e destinatario -\> handshake a
quattro vie).

CAPITOLO 10

ThingSpeak: servizio online per l'analisi di dispositivi IoT e MQTT, che
raccoglie e archivia i dati dei sensori nel cloud e di sviluppare
applicazioni IoT.

CAPITOLO 11

LPWAN: Low Power Wide Area Network è una rete per comunicazioni a lungo
raggio e a basso bit-rate. LPWAN: \* Caratteristiche: \* Low Power:
richiede basso consumo per consentirne una lunga durata; \* Long Range:
utilizzabile a distanze elevate; \* Low Traffic: basso traffico dati,
questi ultimi di dimensioni piccole; \* Low Cost: basso costo; \* Low
Complexity: bassa complessità, sia installazione che utilizzo.

LoRaWAN: tecnologia wireless a bassa potenza che consente ai dispositivi
alimentati a batteria di connettere ad una rete IoT su un lungo raggio,
utilizzando una banda ridotta (in una rete regionale, nazionale o
globale). LoRaWAN: standard aperto a basso costo, gratuito. Si basa su
LoRa.

LoRa: modulazione wireless, utilizzato nelle comunicazioni militari e
spaziali per decenni a causa delle lunghe distanze di comunicazioni e
dalla robustezza alle interferenze.

LoRaWAN: architettura a stella, dove i gateway fungono da bridge
trasparenti che inoltrano i messaggi tra i dispositivi finali e un
server di rete centrale nel back-end. LoRaWAN: Gateway collegati al
server tramite IP, mentre i dispositivi usano comunicazione wireless a
singolo hop su uno o più gateway.

DOMANDE USCITE NEGLI ESAMI SCORSI \#Che cosa è un beacon in una rete
802.11? Chi lo trasmette? La rete 802.11, per funzionare, ha bisogno di
essere rilevata dai dispositivi che hanno intenzione di collegarsi; per
fare ciò è necessario utilizzare i beacon. I beacon sono pacchetti
segnalatori che sfruttano il broadcast per comunicare tutte le attività
a tutti i dispositivi connessi e a tutti quei dispositivi che hanno
intenzione di connettersi alla rete. Un dispositivo, per connettersi ad
una rete 802.11, ha sicuramente bisogno di alcune informazioni
importanti, come l'SSID che corrisponde al nome identificativo della
rete 802.11 alla quale abbiamo intenzione di connetterci.

\#Descrivere le tre classi di funzionamento dei dispositivi LoRaWAN
LoRaWAN è una tecnologia wireless che viene utilizzata da tutti quei
dispositivi IoT che vengono alimentati a batteria; è molto utilizzato in
questo ambito in quanto sfrutta la tecnologia LoRa, una tecnologia che
permette di comunicare con due o più dispositivi a distanze molto
elevate (utilizzato nell'ambito spaziale). LoRaWAN porta con sè tre
classi di funzionamento per i dispositivi: \* Classe A: necessaria per
tutti i dispositivi, supporta la comunicazione bidirezionale con il
gateway. I messaggi di Uplink, dal nodo al gateway, possono essere
inviati in qualsiasi momento. A seguito di un messaggio di Uplink, il
nodo apre due schermate di ricezione (una coincide con lo stesso
canale). Il Network Server risponde tramite gateway con un messaggio di
Downlink. Questa classe è la più efficiente dal punto di vista
energetico ed è utilizzata da quei nodi che cercano di rimanere inattivi
per un tempo più lungo possibili. \* Classe B: prende le caratteristiche
della classe A, ma implementa delle finestre di ricezione programmate
per i messaggi Downlink, inviati dal Network Server tramite gateway. I
nodi aprono periodicamente delle finestre di ricezione, consentendo
l'invio di messaggi in Downlink. Questa classe è utiizzata da quei nodi
che necessitano di ricevere comandi. \* Classe C: prende le
caratteristiche della classe A e della classe B, ma implementa una
finestra di ricezione sempre aperta (tranne quando avviene una
tramissione). Questa classe è utilizzata da quei nodi che hanno finestre
di ricezione vincolate dal punto di vista temporale.

\#Spiegare sinteticamente il funzionamento del protocollo MQTT Il
protocollo MQTT sta per Messagge Queuing Telemetry Transport ed è un
protocollo di trasmissione dati TCP/IP. Viene utilizzato questo
protocollo dai dispositivi IoT che hanno intenzione di comunicare tra di
loro per svolgere determinate funzioni. Il protocollo MQTT si basa su
due principali attori: \* Mittente-Destinatario; \* Broker.

Il mittente invia dei messaggi al destinatario di un certo argomento, e
il destinatario sottoscrive questi messaggi sugli argomenti a lui
interessati. Il Broker, invece, provvede a gestire l'invio e la
ricezione dei messaggi da parte del mittente e da parte del
destinatario.

\#Spiegare il fenomeno dei terminali nascosti nelle reti 802.11 ed
eventuali soluzioni per mitigare il problema. Nelle reti 802.11 esiste
la possibilità che due o più stazioni non riescono a comunicare tra di
loro perché risultano essere molto lontani rispetto al range massimo o
perchè ci sono state delle ritrasmissioni o trasmissioni simultanee su
uno stesso canale di comunicazione. Per evitare questo problema,
utilizziamo una trasmissione TCP/IP handshake a quattro vie e utilizza
due variabili: \* RTS: Request To Send, utilizzato per verificare se un
canale di comunicazione è disponibile per la trasmissione; \* CTS: Clear
To Send, utilizzando come risposta all'autorizzazione di accesso
effettuato nel RTS.

Durante la fase di RTS e CTS, abbiamo un timer stabilito direttamente da
loro stessi -\> viene utilizzato per stabilire per quanto tempo i
restanti dispositivi non possono comunicare con le stazioni attualmente
in comunicazione.

\#Spiegare a cosa serve e come funziona il modulo ADR per le reti
LoRaWAN. LoRaWAN è una tecnologia wireless che viene utilizzata da tutti
quei dispositivi IoT che vengono alimentati a batteria; è molto
utilizzato in questo ambito in quanto sfrutta la tecnologia LoRa, una
tecnologia che permette di comunicare con due o più dispositivi a
distanze molto elevate (utilizzato nell'ambito spaziale). Durante la
comunicazione tra due o più dispositivi, le frequenze utilizzate e il
date-rate vengono modificati in base all'esigenze e dalla distanza:
questo avviene tramite il modulo ADR o Adaptive Date Rate, che permette
di aumentare l'efficienza energetica. I moduli ADR hanno il compito di
captare la quantità di disturbo (SF) e la potenza dei pacchetti (TF) che
provengono dalle singole stazioni. Il nostro obiettivo è di avere un
valore di SF nella media, in quanto: \* Se è molto basso, saremo più
soggetti a perdite di segnale o disturbi; \* Se è molto alto, avremo
poche possibilità di perdite di segnale o disturbo ma avremo
un'efficienza scarsa e un consumo energetico molto alto (obbiettivo
opposto dell'ADR).

\#Spiegare come funzionano e quali sono le differenze tra TDMA e FDMA.
FDMA è una tecnica di accesso multiplo che consiste nella suddivisione
della banda di frequenza disponibile in un numero di
sottobande(sottocanali) che occupino, in frequenza, una banda più
piccola; ognuno di questi sottocanali è assegnato a ciascuna delle
sorgenti di informazione, che lo utilizzerà per trasmettere il segnale.
In ricezione, un'opportuna sequenza di filtri passabanda permetterà di
selezionare il segnale della sorgente di cui si vuole estrarre
l'informazione.

TDMA è una tecnica di accesso multiplo in cui la condivisione del canale
è realizzata mediante ripartizione del tempo di accesso allo stesso da
parte degli utenti.

Le differenze tra FDMA e TDMA sono le seguenti: \* FDMA: \* Avviene la
condivisione della bandwidth tra le diverse stazioni; \* La
sincronizzazione non è richiesta; \* La velocità dei dati è bassa; \*
Poco flessibile. \* TDMA: \* Avviene la condivisione del tempo grazie
all'utilizzo dei satelliti; \* La sincronizzazione è richista; \* La
velocità dei dati è nella media; \* Abbastanza flessibile.

\#Spiegare come funziona un convertitore analogico-digitale. La
conversione analogico-digitale si basa su tre principali fasi: \*
Campionamento: ci consente di trasformare un onda di grandezza analogica
in una grandezza che varia in specifici istanti di tempo, chiamato
periodo di campionamento. Più periodi abbiamo, maggiore sarà
l'accuratezza delle informazioni ma maggiore sarà la durata del
processo. \* Quantizzazione: ci consente di limitare il numero di valori
che vogliamo conservare (introduce un errore -\> sfrutta
approssimazione) \* Codifica: ci consente di prendere i valori ottenuti
nella fase di quantizzazione e di convertirli in segnale digitali
(binario)

\#Descrivere il principio di funzionamento delle modulazioni digitali ed
entrare nel dettaglio di una di loro La modulazione è una tecnica di
trasmissione finalizzata ad imprimere un segnale elettrico, detto
modulante, su un altro segnale elettrico, detto portante. Il risultato
della modulazione è la conversione del segnale modulante dalla banda
base alla banda traslata. La modulante rappresenta quel segnale
elettrico che contiene le informazioni da trasmettere, mentre la
portante è un segnale elettrico a frequenza ben definita (generalmente
alta) e viene utilizzato per essere accoppiata con la modulante per
trasmettere dati tramite canali di comunicazione. La modulazione può
essere di due tipologie: \* Analogico: \* AM; \* FM. \* Digitale: \*
ASK; \* FSK; \* PSK: ampiezza e frequenza della portante rimangono
costanti, mentre la fase può subire dei cambiamenti. Il metodo più
semplice è il metodo BPSK, che consiste nello scambio di fase della
portante di 180° in corrispondenza di un livello alto. Il PSK assicura
un buon livello di immunità ai disturbi e consente delle velocità di
trasmissione elevate, ma richiede un ricetrasmettitore molto complesso.

\#Riassumere il meccanismo di backoff esponenziale per le reti IEEE
802.11. Nelle reti 802.11 esiste la possibilità che possa avvenire una
collisione dovuta durante il trasferimento di pacchetti da due o più
stazioni diverse; per evitare questo problema, si utilizza un timer
chiamato backoff che ha il compito di fermare, per un tempo specifico,
le stazioni prima ancora di poter cominciare a trasmettere i pacchetti
(si evitano appunto collisioni o trasmissioni sovrapposte). Se avessimo
una perdita di pacchetto, la finestra di backoff crescerà
esponenzialmente tramite la formula 2\^m, dove m rappresenta il numero
di pacchetti persi.

\#Nelle reti 802.11, quali sono le differenze tra BSS infrastruttura e
BSS indipendente? BSS è una topologia di rete che consente ai
dispositivi di connettersi alla rete IEEE 802.11 mediante tecnologia
wireless oppure ad-hoc. BSS può essere di due tipologie: \* BSS
Infrastruttura: sfrutta la tecnologiaa wireless (molto comoda, molto
flessibilità, subisce latenza durante la trasmissione pacchetti, poco
costosa, interferenze possibili) \* BSS Indipendente: sfrutta la
tecnologia ad-hoc (poco comoda, molto potente, molto veloce, molto
costosa, 0 latenza, 0 interferenze).

\#Descrivere il sistema di cifratura dei pacchetti utilizzati nella rete
LoRaWAN. Ogni nodo di una rete LoRaWAN dispone delle seguenti
informazioni: \* DevAddr: indirizzo identificativo del device che indica
il nodo nella rete, è a 32 bit. \* AppEUI: identificativo di
applicazione composto da 64 bit; \* NwkSKEY: chiave di sessione di rete
AES-128 bit, utilizzata per controllare l'integrità del messaggio; \*
AppSKEY: chiave di sessione per applicazione AES-128 bit, utilizzata per
cifrare e decifrare il payload dei messaggi per creare un canale di
comunicazione end-to-end

Esistono due modalità per associare un nodo alla rete: \* OTAA: si basa
sul concetto di join prima di poter scambiare dati con il Network Server
(messaggio MAC di join request). Successivamente, il Network Server
risponde con un messaggio MAC di join accept \* ABP: si basa sul
concetto di request join-accept, dove le informazioni vengono
memorizzate direttamente dal nodo.

La crittografia può essere di due tipologie: \* Asimmetrico: \* Utilizza
una chiave pubblica e una chiave privata; \* Utilizzato quando abbiamo
due diversi endpoint. \* Simmetrico: \* Utilizza una sola chiave
privata; \* Utilizzato dove è necessario cifrare dati molto velocemente.

L'algoritmo hash viene utilizzato per controllare l'integrità dei dati e
viene considerato come una firma (hash unidirezionale).

\#Quale è il principio di funzionamento alla base della conversione
digitale-analogica tramite PWM, e come si definisce il duty cycle? La
conversione digitale-analogico è una tecnica di conversione che viene
utilizzata, come dice il nome stesso, per convertire un segnale digitale
(generalmente espresso in codice binario) in un segnale analogico; si
tratta del funzionamento inverso alla conversione analogico-digitale.
Per effettuare la conversione digitale-analogico, abbiamo
necessariamente bisogno di utilizzare il PWM, un segnale ad onda quadra
di duty cycle che ci permette di capire quanta porzione di segnale
stiamo utilizzando. In particolare, il PWM è caratterizzato da: \* T:
periodo del segnale; \* T\_on: lasso di tempo in cui il PWM rimane a
livello alto; \* T\_off: lasso di tempo in cui il PWM rimane a livello
basso.

Il rapporto tra T\_on e T\_off viene definito come duty cycle, ed è
rappresentatno in percentuale.

\#Che cosa è un beacon in una rete IEEE 802.11? Chi trasmette in
modalità infrastruttura e ad-hoc? Quale è l'impatto sulla procedura di
scansione attiva e passiva? La rete 802.11, per funzionare, ha bisogno
di essere rilevata dai dispositivi che hanno intenzione di collegarsi;
per fare ciò è necessario utilizzare i beacon. I beacon sono pacchetti
segnalatori che sfruttano il broadcast per comunicare tutte le attività
a tutti i dispositivi connessi e a tutti quei dispositivi che hanno
intenzione di connettersi alla rete. Un dispositivo, per connettersi ad
una rete 802.11, ha sicuramente bisogno di alcune informazioni
importanti, come l'SSID che corrisponde al nome identificativo della
rete 802.11 alla quale abbiamo intenzione di connetterci.

BSS è una topologia di rete che consente ai dispositivi di connettersi
alla rete IEEE 802.11 mediante tecnologia wireless oppure ad-hoc. BSS
può essere di due tipologie: \* BSS Infrastruttura: sfrutta la
tecnologiaa wireless (molto comoda, molto flessibilità, subisce latenza
durante la trasmissione pacchetti, poco costosa, interferenze possibili)
\* BSS Indipendente: sfrutta la tecnologia ad-hoc (poco comoda, molto
potente, molto veloce, molto costosa, 0 latenza, 0 interferenze).

Passive scanning è un metodo di rilevamento delle vulnerabilità, che si
basa sulle informazioni raccolte dai dati di rete acquisiti da una
stazione di destinazione senza interazione diretta (si basa sullo
sniffing dei pacchetti). I vantaggi e svantaggi del Passive scanning
sono i seguenti: \* Vantaggi: \* Intruso: non lascia tracce che
potrebbero avvisare utenti o amministratori. \* Amministratore: non
causa comportamenti indesiderati sul computer di destinazione. \*
Svantaggi: \* Forti limitazioni ha livello di comunicazione; \* Non è
completo nel dettagio.

Active scanning è come il passive scanning, ma più costoso e meno
affidabile (sia in tempi di attività che affidabilità del sistema).

\#Presentare l'architettura e il funzionamento del protocollo MQTT.
Elencare i diversi attori che compongono il sistema e il loro
comportamento. Soffermarsi sui concetti di topic, keep-alive time, last
wiell and testament e wildcard. Il protocollo MQTT sta per Messagge
Queuing Telemetry Transport ed è un protocollo di trasmissione dati
TCP/IP. Viene utilizzato questo protocollo dai dispositivi IoT che hanno
intenzione di comunicare tra di loro per svolgere determinate funzioni.
Il protocollo MQTT si basa su due principali attori: \*
Mittente-Destinatario; \* Broker.

Il mittente invia dei messaggi al destinatario di un certo argomento, e
il destinatario sottoscrive questi messaggi sugli argomenti a lui
interessati. Il Broker, invece, provvede a gestire l'invio e la
ricezione dei messaggi da parte del mittente e da parte del
destinatario.

MQTT si basa sui seguenti concetti: \* Topic: argomento (codificato in
UTF-8) dove viene mandato al destinatario per svolgere determinati
compiti. Il topic può essere divisi a più livelli tramite l'utilizzo
dello slash (/). \* Keep-Alive time: tempo massimo di comunicazione con
i dispositivi che utilizzano il protocollo MQTT. \* Last will and
testament: gestisce e conserva gli stati dei dispositivi MQTT. \*
Wildcard: utilizzato per cercare la posizione del topic e può essere di
due tipologie: \* Singolo: /home/documenti/+/cartella; \* Multi livello:
/home/documenti/\#
