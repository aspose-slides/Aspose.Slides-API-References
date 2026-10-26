---
title: LoadOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/loadoptions/
---
## LoadOptions classe

Consente di specificare opzioni aggiuntive (come formato o carattere predefinito) durante il caricamento di una presentazione.

Il tipo LoadOptions espone i seguenti membri:

## Costruttori

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/loadoptions/__init__/#) | Crea nuove opzioni di caricamento predefinite. |
| [`__init__(self, load_format)`](/slides/python-net/it/aspose.slides/loadoptions/__init__/#loadformat) | Crea nuove opzioni di caricamento. |

## Proprietà

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/it/aspose.slides/loadoptions/load_format/) | Restituisce o imposta il formato di una presentazione da caricare.<br/>            Lettura/scrittura [`LoadFormat`](/slides/python-net/it/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides/loadoptions/default_regular_font/) | Restituisce o imposta il carattere Regular usato se il carattere sorgente non è trovato.<br/>            Lettura/scrittura **str**. |
| [`default_symbol_font`](/slides/python-net/it/aspose.slides/loadoptions/default_symbol_font/) | Restituisce o imposta il carattere Symbol usato se il carattere sorgente non è trovato.<br/>            Lettura/scrittura **str**. |
| [`default_asian_font`](/slides/python-net/it/aspose.slides/loadoptions/default_asian_font/) | Restituisce o imposta il carattere Asian usato se il carattere sorgente non è trovato.<br/>            Lettura/scrittura **str**. |
| [`password`](/slides/python-net/it/aspose.slides/loadoptions/password/) | Ottiene o imposta la password.<br/>            Lettura/scrittura **str**. |
| [`only_load_document_properties`](/slides/python-net/it/aspose.slides/loadoptions/only_load_document_properties/) | Questa proprietà ha senso se il file di presentazione è protetto da password.<br/>            Il valore true indica che solo le proprietà del documento devono essere caricate da un file di presentazione crittografato<br/>            e la password deve essere ignorata.<br/>            Il valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta<br/>            .<br/>            Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato.<br/>            Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, allora<br/>            le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione.<br/>            Lettura/scrittura **bool**. |
| [`warning_callback`](/slides/python-net/it/aspose.slides/loadoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento<br/>            continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/it/aspose.slides/loadoptions/blob_management_options/) | Rappresenta le opzioni che possono essere usate per gestire il comportamento di gestione dei Binary Large Objects (BLOB),<br/>            come l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono pensate per impostare<br/>            il miglior rapporto prestazioni/consumo di memoria per un determinato ambiente o requisito.<br/>            Un Binary Large Object (BLOB) è un dato binario memorizzato come entità unica – ad es. un BLOB può <br/>            essere un audio, video o la presentazione stessa. |
| [`document_level_font_sources`](/slides/python-net/it/aspose.slides/loadoptions/document_level_font_sources/) | Specifica le sorgenti per i caratteri esterni da utilizzare nella presentazione.<br/>            Questi caratteri sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni |
| [`interruption_token`](/slides/python-net/it/aspose.slides/loadoptions/interruption_token/) | Il token per monitorare le richieste di interruzione.<br/>            <br/>            Questo token gestisce l'intera durata dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento<br/>            o il salvataggio della presentazione, sarà interrotta chiamando il metodo [`InterruptionTokenSource.interrupt`](/slides/python-net/it/aspose.slides/interruptiontokensource/interrupt) di<br/>            [`InterruptionTokenSource`](/slides/python-net/it/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/it/aspose.slides/loadoptions/resource_loading_callback/) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne.<br/>            Lettura/scrittura [`IResourceLoadingCallback`](/slides/python-net/it/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/it/aspose.slides/loadoptions/spreadsheet_options/) | Ottiene le opzioni per i fogli di calcolo. Ad esempio, queste opzioni influenzano il calcolo delle formule per i grafici. |
| [`default_text_language`](/slides/python-net/it/aspose.slides/loadoptions/default_text_language/) | Restituisce o imposta la lingua predefinita per il testo della presentazione.<br/>             Lettura/scrittura **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/it/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.<br/>            <br/>I tipi di oggetti binari incorporati:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/it/aspose.slides/ipresentation/vba_project)<br/>* Dati incorporati OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* Dati binari ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/it/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lettura/scrittura **bool**. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)