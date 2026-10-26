---
title: SVGOptions
second_title: Aspose.Sildes .NET API hivatkozás
description: SVG opciókat képviseli.
type: docs
weight: 4430
url: /hu/aspose.slides.export/svgoptions/
---
## SVGOptions class

SVG opciókat képviseli.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializál egy új SVGOptions példányt. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializál egy új SVGOptions példányt, megadva a link beágyazó vezérlő objektumot. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Visszaadja az alapértelmezett beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a forrás betűtípus hiányában használt betűtípust. Olvasás/írás String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Egy Boolean jelző, amely jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva lesznek (ami esetleg nagyobb fájlt eredményezhet). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. Olvasás/írás Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Lekéri vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen renderelve. Ha `true` értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság `false` értékre van állítva. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Letiltja a FromCornerX és FromCenter gradiensek felosztását. Olvasás/írás Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Az SVG 1.1 nem tartalmazza a jelölők belső határainak meghatározásának képességét. Az Aspose.Slides SVG író motorja megoldást nyújt erre a problémára: levágja a nyíllal ellátott vonal végét, így a vonal nem fedje át a jelölőket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás/írás Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. Olvasás/írás [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Olyan beállításokat biztosít, amelyek szabályozzák a tintobjektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Meghatározza a JPEG kódolás minőségét. Olvasás/írás Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Visszaadja vagy beállítja a metafájl raszterizálásának alacsonyabb felbontási határát. Olvasás/írás Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Ábrázolja a képek tömörítési szintjét |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Ábrázolja a mentési folyamat előrehaladását százalékban jelző visszahívási objektumot. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a shape átalakítás vezérlését. Olvasás/írás [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Meghatározza, hogy a shape megadott forgatását végrehajtsa-e a renderelés során vagy sem. Olvasás/írás Boolean. Az alapértelmezett érték true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. Olvasás/írás Boolean. Az alapértelmezett érték false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. Olvasás/írás Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ISVGOptions](../isvgoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->