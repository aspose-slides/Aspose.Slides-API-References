---
title: SVGOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een SVG-optie voor.
type: docs
weight: 4450
url: /nl/aspose.slides.export/svgoptions/
---
## SVGOptions klasse

Stelt een SVG-optie voor.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialiseert een nieuw exemplaar van de SVGOptions-klasse. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialiseert een nieuw exemplaar van de SVGOptions-klasse met de opgegeven link-embed-controller. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Retourneert standaardinstellingen. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandsgeneratie. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Retourneert instellingen voor de meest nauwkeurige SVG-bestandsgeneratie. Alleen-lezen [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retourneert of stelt het lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/Schrijven String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Een boolse vlag geeft aan of bijgesneden delen deel blijven uitmaken van het document. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bepaalt of de 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Schakelt het splitsen van FromCornerX- en FromCenter-gradients uit. Lezen/Schrijven Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. De Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij knipt het einde van de lijn met pijl af, zodat de lijn geen overlap met markers veroorzaakt. Deze optie schakelt dat gedrag uit. Lezen/Schrijven Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bepaalt een manier om extern geladen lettertypen te verwerken. Lezen/Schrijven [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retourneert of stelt de visuele stijl van de gradient in. Lezen/Schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bepaalt de JPEG-coderingskwaliteit. Lezen/Schrijven Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. Lezen/Schrijven Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stelt het compressieniveau voor afbeeldingen voor |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor het opslaan van voortgangsupdates in percentage voor. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Retourneert en stelt een callback-interface in waarmee de gebruiker de vormconversie kan beheersen. Lezen/Schrijven [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen/Schrijven Boolean. De standaardwaarde is **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bepaalt of de opgegeven rotatie van de vorm moet worden uitgevoerd bij het renderen of niet. Lezen/Schrijven Boolean. Standaardwaarde is true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bepaalt of het tekstframe wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven Boolean. Standaardwaarde is false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bepaalt of de tekst op een dia wordt opgeslagen als grafische weergave. Lezen/Schrijven Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* naamruimte [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->