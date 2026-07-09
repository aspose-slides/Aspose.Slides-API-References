---
title: SwfOptions
second_title: Aspose.Sildes per .NET Riferimento API
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato Swf.
type: docs
weight: 4530
url: /it/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata nel formato Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SwfOptions](swfoptions)() | Costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Specifica se il documento SWF generato deve essere compresso o meno. Il valore predefinito è `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Restituisce o imposta il carattere usato nel caso in cui il carattere di origine non sia trovato. Stringa lettura-scrittura. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Restituisce o imposta lo stile visivo del gradiente. Lettura/scrittura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Specifica la qualità delle immagini JPEG. Il valore predefinito è 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Immagine che verrà mostrata come logo nell'angolo in alto a destra del visualizzatore. L'immagine deve essere PNG 32x64 pixel, altrimenti il logo potrebbe essere visualizzato in modo scorretto. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Ottiene o imposta l'indirizzo ipertestuale completo per un logo. Ha effetto solo se è specificato un [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Mostra/nascondi il riquadro inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Mostra/nascondi il pulsante fullscreen. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Specifica se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Mostra/nascondi il riquadro sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Specifica se mostrare il bordo attorno alle pagine. Il valore predefinito è true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Mostra/nascondi il selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Mostra/nascondi la sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Mostra/nascondi l'intero riquadro superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Booleano lettura/scrittura. Il valore predefinito è **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](../islideslayoutoptions). Questa proprietà non supporta l'assegnazione di oggetti di tipo [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Avvia con il riquadro sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Specifica se il documento SWF generato deve includere il visualizzatore di documenti integrato o meno. Il valore predefinito è `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve gli avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Esempi

Il seguente esempio mostra come convertire PowerPoint in Flash SWF.

```csharp
[C#]
// Istanziare un oggetto Presentation che rappresenta un file di presentazione
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Salvataggio della presentazione e delle pagine delle note
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

## Vedi anche

* classe [SaveOptions](../saveoptions)
* interfaccia [ISwfOptions](../iswfoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->