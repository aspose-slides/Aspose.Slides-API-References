---
title: SVGOptions
second_title: Aspose.Sildes pro .NET referenční příručka API
description: Představuje nastavení SVG.
type: docs
weight: 4410
url: /cs/aspose.slides.export/svgoptions/
---
## SVGOptions třída

Představuje nastavení SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializuje novou instanci třídy SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializuje novou instanci třídy SVGOptions s určením objektu řadiče vkládání odkazů. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Vrací výchozí nastavení. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Vrací nastavení pro nejjednodušší a nejmenší generování SVG souboru. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Vrací nastavení pro nejpřesnější generování SVG souboru. Pouze pro čtení [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo používané v případě, že není nalezeno výchozí písmo. Čtení/zápis String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Příznak typu Boolean určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Určuje, zda je 3D text v SVG zakázán. Čtení/zápis Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaveno na `true`, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Zakazuje rozdělení gradientů FromCornerX a FromCenter. Čtení/zápis Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 postrádá možnost definovat vnitřní odsazení pro značky. Motor pro zápis SVG v Aspose.Slides má řešení tohoto problému: ořezává konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení toto chování vypíná. Čtení/zápis Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Určuje způsob zacházení s externě načtenými fonty. Čtení/zápis [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Určuje kvalitu kódování JPEG. Čtení/zápis Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Vrací nebo nastavuje spodní limit rozlišení pro rasterizaci metafile. Čtení/zápis Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Reprezentuje úroveň komprese obrázků |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. Čtení/zápis [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s JavaScript voláními. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Určuje, zda provést zadanou rotaci tvaru při vykreslování nebo ne. Čtení/zápis Boolean. Výchozí hodnota je true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Určuje, zda bude textový rámeček zahrnut do oblasti vykreslování nebo ne. Čtení/zápis Boolean. Výchozí hodnota je false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Určuje, zda bude text na snímku uložen jako grafika. Čtení/zápis Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [ISVGOptions](../isvgoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->