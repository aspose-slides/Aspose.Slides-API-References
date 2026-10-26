---
title: LoadOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Consente di specificare opzioni aggiuntive, come il formato o il font predefinito, durante il caricamento di una presentazione.
type: docs
weight: 7840
url: /it/aspose.slides/loadoptions/
---
## LoadOptions classe

Consente di specificare opzioni aggiuntive (come il formato o il font predefinito) durante il caricamento di una presentazione.

```csharp
public class LoadOptions : ILoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Crea nuove opzioni di caricamento predefinite. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Crea nuove opzioni di caricamento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Rappresenta le opzioni che possono essere usate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB), ad esempio l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono pensate per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti specifici. Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola, cioè un BLOB può essere un audio, un video o la presentazione stessa. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Restituisce o imposta il font asiatico usato nel caso in cui il font di origine non sia trovato. Lettura/Scrittura String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font regolare usato nel caso in cui il font di origine non sia trovato. Lettura/Scrittura String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Restituisce o imposta il font simbolo usato nel caso in cui il font di origine non sia trovato. Lettura/Scrittura String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/Scrittura String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Specifica le origini dei font esterni da usare nella presentazione. Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Il token per monitorare le richieste di interruzione. Questo token gestisce l'intero ciclo di vita dell'istanza [`IPresentation`](../ipresentation). Qualsiasi operazione a lunga durata, come il caricamento o il salvataggio di una presentazione, sarà interrotta chiamando il metodo [`Interrupt`](../interruptiontokensource/interrupt) di [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Restituisce o imposta il formato di una presentazione da caricare. Lettura/Scrittura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Questa proprietà ha senso se il file della presentazione è protetto da password. Il valore true indica che devono essere caricati solo le proprietà del documento da un file di presentazione crittografato e la password deve essere ignorata. Il valore false indica che l'intera presentazione crittografata deve essere caricata usando la password corretta. Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e viene generata un'eccezione. Lettura/Scrittura Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Ottiene o imposta la password. Lettura/Scrittura String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento di risorse esterne. Lettura/Scrittura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Ottiene le opzioni per i fogli di calcolo. Ad esempio, queste opzioni influenzano il calcolo delle formule per i grafici. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/Scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Vedi anche

* interfaccia [ILoadOptions](../iloadoptions)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->