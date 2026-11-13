---
title: SVGOptions
second_title: Aspose.Sildes .NET API Referencia
description: SVG opciókat képviseli.
type: docs
weight: 4450
url: /hu/aspose.slides.export/svgoptions/
---
## SVGOptions osztály

SVG opciókat képviseli.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Az SVGOptions osztály egy új példányát inicializálja. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Az SVGOptions osztály egy új példányát inicializálja, megadva a ILinkEmbedController objektumot. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Alapértelmezett beállításokat ad vissza. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a forrás betűtípus nem található esetén használt betűtípust. Olvasás/írás String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Egy boolean jelző, amely azt jelzi, hogy a levágott részek a dokumentum részét képezzék-e. Ha true, a levágott részek eltávolításra kerülnek, ha false, a dokumentumba sorosítva maradnak (ami nagyobb fájlméretet eredményezhet). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. Olvasás/írás Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. Ha `true`-ra van állítva, a ligatúrák letiltásra kerülnek a renderelt kimenetben. Alapértelmezésben ez a tulajdonság `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Letiltja a FromCornerX és FromCenter átmenetek felosztását. Olvasás/írás Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Az SVG 1.1 nem támogatja a jelölők behúzásának definiálását. Az Aspose.Slides SVG író motorja megoldást kínál: levágja a nyíllal ellátott vonal végét, így a vonal nem fed le jelölőket. Ez az opció kikapcsolja ezt a viselkedést. Olvasás/írás Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Meghatározza a külső betöltésű betűtípusok kezelésének módját. Olvasás/írás [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja az átmenet vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Opciókat biztosít, amelyek a exportált dokumentum Ink objektumainak megjelenését szabályozzák. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Meghatározza a JPEG kódolás minőségét. Olvasás/írás Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Visszaadja vagy beállítja a metafájl raszterizálás alacsonyabb felbontási határát. Olvasás/írás Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Kép tömörítési szintet képviseli |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Százalékos mentési előrehaladás frissítésekhez egy visszahívási objektumot képviseli. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Visszaadja és beállítja azt a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a formák konvertálásának vezérlését. Olvasás/írás [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyásra kerülnek-e a JavaScript hívásokat tartalmazó hiperhivatkozások. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Meghatározza, hogy a forma megadott forgatását a renderelés során végrehajtják-e. Olvasás/írás Boolean. Az alapértelmezett érték true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Meghatározza, hogy a szövegdoboz bekerül-e a renderelési területbe. Olvasás/írás Boolean. Alapértelmezett érték false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Meghatározza, hogy a dián lévő szöveg grafikai elemként legyen-e mentve. Olvasás/írás Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ISVGOptions](../isvgoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->