# RotorRE
(versione in italiano più in basso)

Collection of files from my IPM Rotor 2 reverse engineering project
For all the info, see https://hackaday.io/project/181937-reverse-engineering-the-rotor

The "schematics" folder contains schematics for the board I've traced so far. Note that that there are different revisions of some of the boards with minimal differences. The revisions I actually traced are reported in the folders; designators in the files match the designators on the physical board, and as far as I know they should match between revisions.

The "hitachi" folder contains the original manual for the HD6305 processor used in the phone AND the Ghidra module I wrote to decompile the ROMs.

Parts of the original manual can be found in the "manual" folder

There's also some of the pictures I took of the internals in the "pics" folder.

I DO have binary images of the ROMs for the boards I have, both for the phone and for the internal card reader. I won't post them here since it's still technically copyrighted code. All of the phone CPU boards in my possession are equipped with ROM version 1.11 from '91, while my card readers have two different FW revisions. Not 100% of the differences yet. I haven't worked on the newer "OV" revisions board yet and I don't plan to unless I absolutely have to.

-------------------------------------------------------

Collezione di file per il mio progetto di reverse engineering del telefono pubblico italiano Rotor 2 (prodotto da IPM)
La documentazione in ITALIANO è contenuta nei file doc.pdf e documentazione.odt; parte dei manuali ufficiali Telecom/SIP/IPM sono disponibili nella cartella "manual"
Attualmente il progetto è arrivato al punto che è possibile inizializzare il telefono ed utilizzarlo per ricevere/effettuare chiamate, come se fosse un Rotor 1; 
tutte le funzioni "avanzate" quali incasso monete, chiamate con schede ecc non sono ancora disponibili

La cartella "schematics" contiene gli schemi di tutte le schede del Rotor 2 + il lettore di schede ("LIOD") in formato KiCad;
notare che le tre varianti principali del telefono (Rotor 1 "due fili", Rotor 2, Rotor OverVoice) differiscono solo nella scheda di Interfaccia Linea,
mentre le altre schede sono intercambiabili e pressochè identiche. Esiste inoltre una variante solo schede, il Rotor 3 "TPDC", che ha in comune il
solo lettore, ed una variante parecchio rara del Rotor 1 (riconoscibile per il foro della serratura posto in basso a destra); di quest'ultimo sono
disponibili gli schemi originali nella cartella "manual" (in ogni caso le IL dei Rotor 1 e 2 sono abbastanza simili fra loro)
Al momento non ho intenzione di disegnare schemi per le interfaccia linea tipo OV se non assolutamente necessario in quanto sono decisamente più moderne
delle altre e quindi più rognose da analizzare.

La cartella "hitachi" contiene il manuale originale del microcontrollore HD6305 (instruction set Motorola 6805) del telefono, più un modulo per Ghidra.

La cartella "pics" contiene semplicemente alcune foto dell'interno di un Rotor 2.

Sono in possesso delle immagini delle ROM dei micro delle tre varianti del telefono + del lettore (ma non di tutte le revisioni del software), ma NON
le pubblicherò qui dato che tecnicamente si tratta di codice coperto da copyright.

