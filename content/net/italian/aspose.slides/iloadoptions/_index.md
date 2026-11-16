---
title: ILoadOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Consente di specificare opzioni aggiuntive, come il formato o il font predefinito, durante il caricamento di una presentazione.
type: docs
weight: 6360
url: /it/aspose.slides/iloadoptions/
---
## ILoadOptions interfaccia

Consente di specificare opzioni aggiuntive (come il formato o il font predefinito) durante il caricamento di una presentazione.

```csharp
public interface ILoadOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Rappresenta le opzioni che possono essere usate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB) , come l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono concepite per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti specifici. Un Binary Large Object (BLOB) è un dato binario memorizzato come un'unica entità – ad es. un BLOB può essere un audio, un video o la presentazione stessa. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Restituisce o imposta il font asiatico usato nel caso in cui il font sorgente non sia trovato. Lettura-scrittura String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font regolare usato nel caso in cui il font sorgente non sia trovato. Lettura-scrittura String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Restituisce o imposta il font simbolo usato nel caso in cui il font sorgente non sia trovato. Lettura-scrittura String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/scrittura String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Specifica le origini dei font esterni da usare nella presentazione. Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Il token per monitorare le richieste di interruzione. Questo token gestisce l'intera durata dell'istanza [`IPresentation`](../ipresentation). Qualsiasi operazione a lungo termine, come il caricamento o il salvataggio della presentazione, sarà interrotta chiamando il metodo [`Interrupt`](../iinterruptiontokensource/interrupt) di [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Restituisce o imposta il formato di una presentazione da caricare. Lettura/scrittura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Questa proprietà ha senso se il file della presentazione è protetto da password. Il valore true indica che solo le proprietà del documento devono essere caricate da un file di presentazione crittografato e che la password deve essere ignorata. Il valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta. Se la presentazione non è crittografata, il valore della proprietà viene sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà generata un'eccezione. Lettura-scrittura Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Ottiene o imposta la password. Lettura-scrittura String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. Lettura/scrittura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Rappresenta le opzioni che possono essere usate per specificare il comportamento aggiuntivo dei fogli di calcolo. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve gli avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Vedi anche

* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->