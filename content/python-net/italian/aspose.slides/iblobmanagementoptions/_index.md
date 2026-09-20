---
title: IBlobManagementOptions class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe

Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola - ovvero BLOB può essere 
            audio, video o la presentazione stessa. Diverse tecniche vengono utilizzate per ottimizzare il consumo di memoria 
            durante il lavoro con i BLOB - che erano già memorizzati nella presentazione o aggiunti successivamente in modo programmato. 
            Utilizzando [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions) è possibile modificare diversi aspetti del comportamento relativi alla gestione dei BLOB 
            per la durata dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation).

The IBlobManagementOptions type exposes the following members:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della fonte - file <br/>            o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la fonte. Questo aiuta <br/>            a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la fonte (stream o file) <br/>            non può essere modificata durante la durata dell'istanza Presentation. Questo è un esempio: |
| [`is_temporary_files_allowed`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Questa proprietà definisce se è possibile creare file temporanei durante il lavoro con i BLOB, il che riduce notevolmente <br/>            il consumo di memoria ma richiede permessi per creare file.<br/>            Tutti i file saranno eliminati al termine del lavoro sulla presentazione. |
| [`temp_files_root_path`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Il percorso radice dove saranno creati i file temporanei. Per impostazione predefinita viene utilizzata la directory temporanea di sistema. <br/>            Il processo di hosting deve avere i permessi per <br/>            creare file e cartelle in quel percorso. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB<br/>            vengono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Utilizza<br/>            questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti. |

### Vedi anche
* classe [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)