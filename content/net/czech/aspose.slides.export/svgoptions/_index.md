---
title: SVGOptions
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje možnosti SVG.
type: docs
weight: 4450
url: /cs/aspose.slides.export/svgoptions/
---
## SVGOptions třída

Represents an SVG options.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Vrací výchozí nastavení. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Vrací nastavení pro nejjednodušší a nejmenší generování SVG souboru. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Vrací nastavení pro nejpřesnější generování SVG souboru. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že není nalezeno zdrojové písmo. Čtení/zápis String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Boolean příznak, který určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou serializovány v dokumentu (což může vést k většímu souboru) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Určuje, zda je 3D text v SVG zakázán. Čtení/zápis Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Získá nebo nastaví hodnotu určující, zda je text vykreslován bez použití ligatur. Pokud je nastavena na `true`, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Zakáže rozdělení gradientů FromCornerX a FromCenter. Čtení/zápis Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 postrádá možnost definovat odsazení pro značky. SVG zapisovací engine Aspose.Slides má pro tento problém řešení: ořízne konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení vypne takové chování. Čtení/zápis Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Určuje způsob zacházení s externě načtenými fonty. Čtení/zápis [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze pro čtení [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Určuje kvalitu JPEG kódování. Čtení/zápis Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Vrací nebo nastavuje spodní limit rozlišení pro rasterizaci metafile. Čtení/zápis Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Reprezentuje úroveň komprese obrázků |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Čtení/zápis [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Určuje, zda při renderování provést specifikovanou rotaci tvaru, nebo ne. Čtení/zápis Boolean. Výchozí hodnota je true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Určuje, zda bude textový rám zahrnut v renderovací oblasti, nebo ne. Čtení/zápis Boolean. Výchozí hodnota je false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Určuje, zda bude text na snímku uložen jako grafika. Čtení/zápis Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [ISVGOptions](../isvgoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->