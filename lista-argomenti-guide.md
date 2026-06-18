# Lista Argomenti: Guide Pratiche Linux & Open Source

> **Target**: Utenti che vogliono riottenere controllo e privacy del proprio PC con la semplicità di un sistema Windows.
> **Formato**: Ogni argomento è pensato come guida scritta + video vlog.
> Stato: da sviluppare

---

## Strategia editoriale

Il percorso narrativo segue il viaggio naturale dell'utente:
**Perché uscire da Windows → Come iniziare → Vita quotidiana su Linux → Strumenti di privacy avanzati**

Ogni guida deve essere autonoma (si legge/guarda senza le precedenti) ma fa parte di un percorso coerente.

---

## Argomenti

### 1. Windows 11 ti spia: cosa raccoglie davvero Microsoft e perché Linux è diverso
**Perché è prioritario**: È il gancio emotivo che motiva il cambio. Argomento molto cercato (telemetria Windows 11, privacy Microsoft 2026) e perfetto come primo video vlog — crea indignazione e curiosità.
- Cosa raccoglie Windows 11 di default (DiagTrack, Copilot, annunci personalizzati)
- Come funziona la telemetria e dove finiscono i dati
- Confronto diretto: cosa NON raccoglie Linux per sua natura (codice aperto, no vendor lock-in)
- Conclusione: Linux non è la soluzione per geek, è la risposta logica a un problema reale

---

### 2. Quale distribuzione Linux scegliere: guida per chi viene da Windows
**Perché è prioritario**: La confusione tra distro è il primo ostacolo. Risposta chiara e pratica riduce il tasso di abbandono.
- Linux Mint: la più simile a Windows, ideale per il primo approccio
- Ubuntu: la più supportata, enorme comunità e documentazione
- Zorin OS: progettata esplicitamente per utenti Windows
- Tabella comparativa: semplicità / privacy / supporto hardware
- Raccomandazione diretta (niente "dipende"): Linux Mint Cinnamon per la maggior parte degli utenti

---

### 3. Dual boot: usa Linux e Windows sullo stesso PC senza scegliere
**Perché è prioritario**: Elimina la paura dell'impegno. Abbassa drasticamente la barriera all'ingresso.
- Cosa è il dual boot e come funziona al riavvio
- Partizione disco: quanto spazio riservare a Linux
- Step-by-step: installazione parallela a Windows
- Come tornare a Windows se qualcosa va storto (sicurezza psicologica)

---

### 4. Installare Linux Mint step by step: dalla chiavetta USB al desktop funzionante
**Perché è prioritario**: La guida più pratica e cercata. Punto d'ingresso concreto dopo aver scelto la distro.
- Creare la chiavetta USB con Ventoy o Balena Etcher
- Boot da USB: come entrare nel BIOS/UEFI
- Installazione guidata con screenshot
- Primo avvio e aggiornamenti iniziali
- Dove trovare aiuto se qualcosa non funziona

---

### 5. Le alternative open source ai programmi che usi ogni giorno
**Perché è prioritario**: L'obiezione più comune è "ma i miei programmi non ci sono". Sfatarla con concretezza.
- Microsoft Office → LibreOffice (Writer, Calc, Impress)
- Photoshop → GIMP per il fotoritocco, Inkscape per la grafica vettoriale
- Windows Media Player / VLC (già cross-platform, nessun cambiamento)
- Notepad++ → Kate o Gedit
- Zoom / Teams → Jitsi Meet (self-hosted), Element (Matrix)
- Google Chrome → Firefox con privacy configurata
- Tabella riassuntiva scaricabile

---

### 6. Come installare programmi su Linux: Software Center, Flatpak e terminale
**Perché è prioritario**: Il secondo ostacolo dopo la scelta della distro. Demistificare il gestore pacchetti è fondamentale.
- Il Software Center: installare programmi come su uno smartphone
- Flatpak e Flathub: il "App Store" universale di Linux (4+ miliardi di download nel 2026)
- APT da terminale: i 3 comandi che bastano (`update`, `upgrade`, `install`)
- Snap: quando usarlo e quando evitarlo
- Regola pratica: usa Flatpak per le app desktop, APT per gli strumenti di sistema

---

### 7. Navigare anonimi: configurare Firefox per la massima privacy
**Perché è prioritario**: Firefox è già il browser di default su molte distro Linux. Configurarlo bene è un passo immediato e ad alto impatto visibile.
- Enhanced Tracking Protection: da Standard a Strict in 30 secondi
- Estensioni essenziali: uBlock Origin, Multi-Account Containers
- Impostazioni about:config consigliate (senza impazzire)
- DNS over HTTPS: cos'è e come abilitarlo
- Cosa evitare: account Firefox, sincronizzazione cloud
- Alternativa avanzata: Mullvad Browser per chi vuole il massimo

---

### 8. Backup automatico con Timeshift: metti Linux al sicuro prima di sbagliare
**Perché è prioritario**: La paura di "rompere qualcosa" è il freno psicologico più forte. Timeshift lo elimina.
- Cos'è uno snapshot e perché è diverso da un backup tradizionale
- Installare e configurare Timeshift in 5 minuti
- Pianificazione automatica degli snapshot
- Come ripristinare il sistema in caso di errore (demo pratica)
- Dove salvare i backup: disco esterno vs partizione separata

---

### 9. Cifrare i file con VeraCrypt: i tuoi dati al sicuro anche se perdi il PC
**Perché è prioritario**: Argomento di alto impatto emotivo e pratico. La cifratura sembrava roba da hacker, ora è accessibile a tutti.
- Perché la password di accesso al PC non basta (disco rimovibile, accesso fisico)
- Installare VeraCrypt su Linux
- Creare un volume cifrato passo dopo passo
- Montare e smontare il volume per l'uso quotidiano
- Caso d'uso pratico: cartella documenti privati, backup cifrato su chiavetta

---

### 10. Il tuo cloud privato con Nextcloud: addio Google Drive e OneDrive
**Perché è prioritario**: Google Drive e OneDrive sono i servizi più usati. Sostituirli con qualcosa di proprio è il salto più simbolico verso l'autonomia digitale.
- Perché i cloud commerciali leggono i tuoi file (termini di servizio reali)
- Cos'è Nextcloud e cosa offre (file sync, calendario, contatti, foto)
- Due modalità: VPS economico ($5/mese) vs Raspberry Pi in casa
- Installazione con Nextcloud AIO e Docker
- App mobile: sincronizzare telefono e PC
- Nextcloud vs Google Drive: confronto funzionalità

---

### 11. Password manager open source: Bitwarden e KeePassXC spiegati semplice
**Perché è prioritario**: La gestione delle password è il problema di sicurezza più diffuso. Strumento immediato, non richiede di cambiare OS.
- Il problema: stessa password ovunque, password deboli, browser che le salva in chiaro
- Bitwarden: open source, cloud cifrato, gratuito, app su tutti i dispositivi
- KeePassXC: 100% locale, nessun cloud, per chi non si fida di niente e nessuno
- Come migrare le password dal browser a Bitwarden in 10 minuti
- Funzionalità extra: generatore di password, autofill, 2FA integrato

---

### 12. VPN su Linux: quale scegliere, come installarla e quando usarla davvero
**Perché è prioritario**: Le VPN sono molto cercate ma spesso mal capite. Una guida onesta e pratica costruisce autorevolezza.
- Cosa fa una VPN (e cosa NON fa — sfatare i miti del marketing)
- VPN open source consigliate: ProtonVPN (gratuita), Mullvad (anonima)
- WireGuard: il protocollo moderno già integrato in Linux
- Installare ProtonVPN su Linux Mint con interfaccia grafica
- Quando usarla: WiFi pubblico, censura, accesso a contenuti geografici
- Quando NON è necessaria: a casa con connessione privata

---

### 13. Personalizzare Linux: fallo sembrare Windows, macOS o qualcosa di unico
**Perché è prioritario**: Contenuto visivo per eccellenza, ideale per vlog. Dimostra che Linux non è solo terminale e righe di testo.
- Temi e icone: installare un look simile a Windows 11 in 10 minuti
- Cambiare desktop environment: differenza tra GNOME, KDE, Cinnamon, XFCE
- Conky e widget sul desktop
- Dock e pannelli: configurare la barra delle applicazioni
- Wallpaper dinamici e animazioni
- Prima/dopo: trasformazione completa del desktop (ottimo formato video)

---

### 14. Il terminale non fa paura: i 10 comandi Linux che cambiano la vita
**Perché è prioritario**: Il terminale spaventa i principianti ma è usato in quasi ogni guida. Una lezione dedicata abbassa la barriera emotiva per tutte le guide successive.
- Perché il terminale esiste e quando è più veloce del mouse
- `ls`, `cd`, `pwd` — orientarsi nel filesystem
- `sudo apt update && sudo apt upgrade` — aggiornare tutto
- `cp`, `mv`, `rm` — gestire file da riga di comando
- `grep` — cercare testo nei file
- Tab completion e history: i due trucchi che cambiano tutto
- Cosa fare se si sbaglia un comando (ctrl+C, man, --help)

---

### 15. Stampare, scannerizzare e hardware su Linux: guida alla compatibilità
**Perché è prioritario**: È il punto di attrito più sottovalutato nel passaggio a Linux. Una guida pratica qui risolve frustrazioni reali.
- Come Linux riconosce le stampanti (CUPS)
- Marchi consigliati per compatibilità totale (Brother, HP)
- Installare driver stampante step by step
- Scanner: Simple Scan funziona meglio di quanto si pensi
- Webcam, microfono e periferiche USB: plug-and-play nella maggior parte dei casi
- Cosa fare se una periferica non funziona (community, forum, driver AUR)

---

## Note di produzione

- **Ordine consigliato per i video**: 1 → 2 → 4 → 3 → 5 → 6 → 7 → 8 → 11 → 12 → 9 → 10 → 13 → 14 → 15
- **Video "gancio"**: #1 e #13 sono i più adatti per i Reels/Shorts — alta componente visiva o emotiva
- **Guide scaricabili**: #5 (tabella alternative) e #14 (cheat sheet terminale) si prestano bene come PDF lead magnet
- **Argomenti evergreen**: tutti questi argomenti restano validi a lungo, nessuna dipendenza da notizie del momento