---
title: SVGOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een SVG-optie voor.
type: docs
weight: 4430
url: /nl/aspose.slides.export/svgoptions/
---
## SVGOptions klasse

Stelt een SVG-optie voor.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialiseert een nieuw exemplaar van de SVGOptions klasse. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialiseert een nieuw exemplaar van de SVGOptions klasse waarbij het link-embedcontroller-object wordt gespecificeerd. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Geeft de standaardinstellingen terug. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Geeft instellingen voor de eenvoudigste en kleinste SVG-bestandgeneratie terug. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Geeft instellingen voor de meest nauwkeurige SVG-bestandgeneratie terug. Alleen-lezen [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/Schrijven String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Een boolse vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Als waar worden de bijgesneden delen verwijderd, als onwaar worden ze geserialiseerd in het document (wat mogelijk tot een groter bestand kan leiden). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bepaalt of de 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Bepaalt of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard staat deze eigenschap ingesteld op `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Lezen/Schrijven Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. De Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij snijdt het einde van de lijn met een pijl af, zodat de lijn geen markers overlapt. Deze optie schakelt dit gedrag uit. Lezen/Schrijven Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bepaalt de manier waarop extern geladen lettertypen worden afgehandeld. Lezen/Schrijven [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft de visuele stijl van de gradiënt terug of stelt deze in. Lezen/Schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bepaalt de JPEG-codeerkwaliteit. Lezen/Schrijven Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Geeft de onderste resolutielimiet voor metafile-rasterisatie terug of stelt deze in. Lezen/Schrijven Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stelt het compressieniveau van afbeeldingen voor |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor het opslaan van voortgangsupdates in percentage voor. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Geeft een callback-interface terug en stelt deze in waarmee de gebruiker shape-conversie kan controleren. Lezen/Schrijven [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-aanroepen worden overgeslagen bij het opslaan van de presentatie. Lezen/Schrijven Boolean. De standaardwaarde is **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bepaalt of de opgegeven rotatie van de shape wordt uitgevoerd bij het renderen of niet. Lezen/Schrijven Boolean. Standaardwaarde is true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bepaalt of het tekstframe wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven Boolean. Standaardwaarde is false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bepaalt of de tekst op een dia wordt opgeslagen als grafische weergave. Lezen/Schrijven Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->