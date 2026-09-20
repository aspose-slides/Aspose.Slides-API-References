---
title: ILoadOptions class
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/iloadoptions/
---
## ILoadOptions classe

Permette di specificare opzioni aggiuntive (come il formato o il carattere predefinito) durante il caricamento di una presentazione.

Il tipo ILoadOptions espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/it/aspose.slides/iloadoptions/load_format/) | Restituisce o imposta il formato di una presentazione da caricare.<br/>            Lettura/scrittura [`LoadFormat`](/slides/python-net/it/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides/iloadoptions/default_regular_font/) | Restituisce o imposta il font Regolare usato nel caso il font di origine non venga trovato.<br/>            Lettura-scrittura **str**. |
| [`default_symbol_font`](/slides/python-net/it/aspose.slides/iloadoptions/default_symbol_font/) | Restituisce o imposta il font Simbolo usato nel caso il font di origine non venga trovato.<br/>            Lettura-scrittura **str**. |
| [`default_asian_font`](/slides/python-net/it/aspose.slides/iloadoptions/default_asian_font/) | Restituisce o imposta il font Asiatica usato nel caso il font di origine non venga trovato.<br/>            Lettura-scrittura **str**. |
| [`password`](/slides/python-net/it/aspose.slides/iloadoptions/password/) | Ottiene o imposta la password.<br/>            Lettura-scrittura **str**. |
| [`only_load_document_properties`](/slides/python-net/it/aspose.slides/iloadoptions/only_load_document_properties/) | Questa proprietà ha senso, se il file della presentazione è protetto da password.<br/>            Il valore true indica che devono essere caricati solo le proprietà del documento da un file di presentazione cifrato e la password deve essere ignorata.<br/>            Il valore false indica che l'intera presentazione cifrata deve essere caricata usando la password corretta.<br/>            Se la presentazione non è cifrata, il valore della proprietà è sempre ignorato.<br/>            Se le proprietà del documento di un file cifrato non sono pubbliche e il valore della proprietà è true, allora le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione.<br/>            Lettura-scrittura **bool**. |
| [`warning_callback`](/slides/python-net/it/aspose.slides/iloadoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento <br/>            continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/it/aspose.slides/iloadoptions/blob_management_options/) | Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB),<br/>            come l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono destinate a impostare<br/>            il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari.<br/>            Un Binary Large Object (BLOB) è un dato binario memorizzato come entità unica – ad es. un BLOB può <br/>            essere un audio, video o la presentazione stessa. |
| [`document_level_font_sources`](/slides/python-net/it/aspose.slides/iloadoptions/document_level_font_sources/) | Specifica le sorgenti per i font esterni da utilizzare nella presentazione.<br/>            Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni |
| [`interruption_token`](/slides/python-net/it/aspose.slides/iloadoptions/interruption_token/) | Il token per monitorare le richieste di interruzione.<br/>            <br/>            Questo token gestisce l'intera durata dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). Qualsiasi operazione a lungo termine, come il caricamento o il salvataggio della presentazione, sarà interrotta chiamando il metodo [`IInterruptionTokenSource.interrupt`](/slides/python-net/it/aspose.slides/iinterruptiontokensource/interrupt) dell'[`IInterruptionTokenSource`](/slides/python-net/it/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/it/aspose.slides/iloadoptions/resource_loading_callback/) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne.<br/>            Lettura/scrittura [`IResourceLoadingCallback`](/slides/python-net/it/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/it/aspose.slides/iloadoptions/spreadsheet_options/) | Rappresenta le opzioni che possono essere utilizzate per specificare il comportamento aggiuntivo dei fogli di calcolo. |
| [`default_text_language`](/slides/python-net/it/aspose.slides/iloadoptions/default_text_language/) | Restituisce o imposta la lingua predefinita per il testo della presentazione.<br/>             Lettura/scrittura **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/it/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.<br/>            <br/>I tipi di oggetti binari incorporati:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/it/aspose.slides/ipresentation/vba_project)<br/>* Dati incorporati OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* Dati binari ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/it/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lettura/scrittura **bool**. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)