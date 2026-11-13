---
title: LoadOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Consente di specificare opzioni aggiuntive come formato o font predefinito durante il caricamento di una presentazione.
type: docs
weight: 7860
url: /it/aspose.slides/loadoptions/
---
## classe LoadOptions

Consente di specificare opzioni aggiuntive (come il formato o il font predefinito) durante il caricamento di una presentazione.

```csharp
public class LoadOptions : ILoadOptions
```

## Costruttori

| Name | Description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Crea nuove opzioni di caricamento predefinite. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Crea nuove opzioni di caricamento. |

## Proprietà

| Name | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Rappresenta le opzioni che possono essere usate per gestire il comportamento di gestione dei Binary Large Objects (BLOBs), come l'uso di file temporanei o il numero massimo di byte dei BLOBs in memoria. Queste opzioni sono destinate a impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari. Un Binary Large Object (BLOB) è un dato binario memorizzato come entità unica, ad esempio un BLOB può essere un audio, un video o la presentazione stessa. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Restituisce o imposta il font asiatico usato nel caso in cui il font di origine non venga trovato. Stringa lettura/scrittura. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font regolare usato nel caso in cui il font di origine non venga trovato. Stringa lettura/scrittura. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Restituisce o imposta il font simbolo usato nel caso in cui il font di origine non venga trovato. Stringa lettura/scrittura. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Restituisce o imposta la lingua predefinita per il testo della presentazione. Stringa lettura/scrittura. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Specifica le font esterne da utilizzare nella presentazione. Queste font sono disponibili per la presentazione per tutta la sua durata e non sono condivise con altre presentazioni. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Il token per monitorare le richieste di interruzione. Questo token gestisce l'intera durata dell'istanza [`IPresentation`](../ipresentation). Qualsiasi operazione a lunga durata, come il caricamento o il salvataggio di una presentazione, sarà interrotta chiamando il metodo [`Interrupt`](../interruptiontokensource/interrupt) del [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Restituisce o imposta il formato della presentazione da caricare. [`LoadFormat`](../loadformat) lettura/scrittura. |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Questa proprietà ha senso se il file della presentazione è protetto da password. Il valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione crittografato e la password deve essere ignorata. Il valore false indica che l'intera presentazione crittografata deve essere caricata usando la password corretta. Se la presentazione non è crittografata, il valore della proprietà viene sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà generata un'eccezione. Booleano lettura/scrittura. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Ottiene o imposta la password. Stringa lettura/scrittura. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. [`IResourceLoadingCallback`](../iresourceloadingcallback) lettura/scrittura. |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Ottiene le opzioni per i fogli di calcolo. Ad esempio, queste opzioni influenzano il calcolo delle formule per i grafici. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento proseguire o essere interrotto. [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) lettura/scrittura. |

### Vedi anche

* interfaccia [ILoadOptions](../iloadoptions)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->