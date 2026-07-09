---
title: SVGOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un'opzione SVG.
type: docs
weight: 4430
url: /it/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Rappresenta un'opzione SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inizializza una nuova istanza della classe SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inizializza una nuova istanza della classe SVGOptions specificando l'oggetto controller di incorporamento dei collegamenti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Restituisce le impostazioni predefinite. Solo lettura [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Restituisce le impostazioni per la generazione del file SVG più semplice e più piccolo. Solo lettura [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Restituisce le impostazioni per la generazione del file SVG più accurata. Solo lettura [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font usato nel caso in cui il font di origine non sia trovato. Lettura/Scrittura String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se vero le parti ritagliate saranno rimosse, se falso saranno serializzate nel documento (il che può portare a un file più grande). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina se il testo 3D è disabilitato in SVG. Lettura/Scrittura Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato su `true`, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/Scrittura Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 non consente di definire gli interni per i marker. Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, quindi la linea non si sovrappone ai marker. Questa opzione disattiva tale comportamento. Lettura/Scrittura Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina il modo di gestire i font caricati esternamente. Lettura/Scrittura [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Restituisce o imposta lo stile visivo del gradiente. Lettura/Scrittura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina la qualità della codifica JPEG. Lettura/Scrittura Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/Scrittura Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Rappresenta il livello di compressione delle immagini |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di progresso in percentuale. Vedi [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione delle forme. Lettura/Scrittura [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/Scrittura Boolean. Il valore predefinito è **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Lettura/Scrittura Boolean. Il valore predefinito è true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Lettura/Scrittura Boolean. Il valore predefinito è false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina se il testo su una diapositiva sarà salvato come grafica. Lettura/Scrittura Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto. Lettura/Scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Vedi anche

* classe [SaveOptions](../saveoptions)
* interfaccia [ISVGOptions](../isvgoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->