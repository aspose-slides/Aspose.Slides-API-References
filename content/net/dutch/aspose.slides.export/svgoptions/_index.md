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

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialiseert een nieuw exemplaar van de SVGOptions klasse. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialiseert een nieuw exemplaar van de SVGOptions klasse met vermelding van het link-embedcontrollerobject. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Retourneert standaardinstellingen. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Retourneert instellingen voor de eenvoudigste en kleinste generatie van SVG-bestanden. Alleen-lezen [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Retourneert instellingen voor de meest nauwkeurige generatie van SVG-bestanden. Alleen-lezen [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lees-schrijven String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Een booleaanse vlag geeft aan of de bijgesneden delen deel van het document blijven. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk leidt tot een groter bestand). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bepaalt of de 3D-tekst is uitgeschakeld in SVG. Lees-schrijven Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Lees-schrijven Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 mist de mogelijkheid om insluitsels voor markers te definiëren. De SVG-schrijfmotor van Aspose.Slides heeft een tijdelijke oplossing voor dat probleem: hij kapaart het einde van een lijn met een pijl af, zodat de lijn de markers niet overlapt. Deze optie schakelt dat gedrag uit. Lees-schrijven Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bepaalt een manier om extern geladen lettertypen te behandelen. Lees-schrijven [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retourneert of stelt de visuele stijl van de gradient in. Lees-schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van inktobjecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bepaalt de JPEG-coderingskwaliteit. Lees-schrijven Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. Lees-schrijven Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stelt het compressieniveau van afbeeldingen voor |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callbackobject voor het opslaan van voortgangsupdates in percentage voor. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te beheersen. Lees-schrijven [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lees-schrijven Boolean. De standaardwaarde is **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bepaalt of de opgegeven rotatie van de vorm wordt uitgevoerd bij het renderen of niet. Lees-schrijven Boolean. Standaardwaarde is true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bepaalt of het tekstframe al dan niet wordt opgenomen in een rendergebied. Lees-schrijven Boolean. Standaardwaarde is false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bepaalt of de tekst op een dia wordt opgeslagen als grafische weergave. Lees-schrijven Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lees-schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* naamruimte [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->