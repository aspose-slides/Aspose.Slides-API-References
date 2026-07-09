---
title: SVGOptions
second_title: Aspose.Sildes pro .NET API Referenci
description: Reprezentuje možnosti SVG.
type: docs
weight: 4430
url: /cs/aspose.slides.export/svgoptions/
---
## SVGOptions třída

Reprezentuje možnosti SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializuje novou instanci třídy SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializuje novou instanci třídy SVGOptions s určením objektu kontroleru vkládání odkazů. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Vrací výchozí nastavení. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Vrací nastavení pro nejjednodušší a nejmenší generování souboru SVG. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Vrací nastavení pro nejpřesnější generování souboru SVG. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. Čtení/Zápis String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Příznak typu Boolean určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Určuje, zda je 3D text v SVG zakázán. Čtení/Zápis Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na `true`, ligatury budou ve výstupním renderu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Zakazuje dělení gradientů FromCornerX a FromCenter. Čtení/Zápis Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 postrádá schopnost definovat odsazení pro značky. Engine pro zápis SVG v Aspose.Slides má řešení tohoto problému: ořízne konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení tuto funkci vypne. Čtení/Zápis Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Určuje způsob zacházení s externě načtenými fonty. Čtení/Zápis [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/Zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Určuje kvalitu kódování JPEG. Čtení/Zápis Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Vrací nebo nastavuje dolní limit rozlišení pro rasterizaci metsouboru. Čtení/Zápis Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Reprezentuje úroveň komprese obrázků |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. Čtení/Zápis [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení/Zápis Boolean. Výchozí hodnota je **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Určuje, zda provést specifikovanou rotaci tvaru při renderování nebo ne. Čtení/Zápis Boolean. Výchozí hodnota je true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Určuje, zda bude textový rámec zahrnut do oblasti renderování nebo ne. Čtení/Zápis Boolean. Výchozí hodnota je false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Určuje, zda bude text na snímku uložen jako grafika. Čtení/Zápis Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen. Čtení/Zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [ISVGOptions](../isvgoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->