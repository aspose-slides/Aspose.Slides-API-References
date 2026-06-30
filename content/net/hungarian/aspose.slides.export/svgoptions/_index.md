---
title: SVGOptions
second_title: Aspose.Sildes .NET API referenciája
description: SVG opciókat képvisel.
type: docs
weight: 4410
url: /hu/aspose.slides.export/svgoptions/
---
## SVGOptions osztály

Represents an SVG options.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Új SVGOptions osztálypéldányt inicializál. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Új SVGOptions osztálypéldányt inicializál a link beágyazási vezérlő objektum megadásával. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Visszaadja az alapértelmezett beállításokat. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálás beállításait. Csak olvasható [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Visszaadja a legpontosabb SVG fájl generálás beállításait. Csak olvasható [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a forrásbetűtípus hiánya esetén használt betűtípust. Olvasás-írás String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Logikai jelző, amely jelzi, hogy a levágott részek a dokumentum részeként maradjanak-e. Ha igaz, a levágott részek eltávolításra kerülnek; ha hamis, a dokumentumban sorosítva maradnak (ami nagyobb fájlméretet eredményezhet). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. Olvasás/írás Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Beállítja vagy lekéri, hogy a szöveget ligatúrák használata nélkül jelenítsék-e meg. `true` érték esetén a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezésben a tulajdonság `false` értéken van. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Letiltja a FromCornerX és FromCenter gradientek felosztását. Olvasás/írás Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Az SVG 1.1 nem támogatja a jelölők belső távolságának meghatározását. Az Aspose.Slides SVG írómotor megkerülést alkalmaz: levágja a nyíllal végződő vonal végét, így a vonal nem fed le jelölőket. Ez a beállítás letiltja ezt a viselkedést. Olvasás/írás Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. Olvasás/írás [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Lehetőségeket biztosít az exportált dokumentumban az Ink objektumok megjelenésének szabályozásához. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Meghatározza a JPEG kódolás minőségét. Olvasás/írás Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Visszaadja vagy beállítja a metafájl rasterizálásának alsó felbontási határát. Olvasás/írás Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Kép tömörítési szintet képviseli |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban adja vissza. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a alakzat konverziójának vezérlését. Olvasás/írás [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyják-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Meghatározza, hogy a megjelenítéskor a megadott forgatást alkalmazzuk-e az alakzatra vagy sem. Olvasás/írás Boolean. Az alapértelmezett érték true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Meghatározza, hogy a szövegkeret bekerüljön-e a megjelenítési területbe vagy sem. Olvasás/írás Boolean. Az alapértelmezett érték false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. Olvasás/írás Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ISVGOptions](../isvgoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->