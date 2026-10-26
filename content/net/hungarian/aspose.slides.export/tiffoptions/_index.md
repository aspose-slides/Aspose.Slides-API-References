---
title: TiffOptions
second_title: Aspose.Sildes .NET API referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció TIFF formátumban.
type: docs
weight: 4570
url: /hu/aspose.slides.export/tiffoptions/
---
## TiffOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció TIFF formátumban.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [TiffOptions](tiffoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Meghatározza a színkép fekete-fehér képpé konvertálásához használt algoritmust. Ez a beállítás csak akkor kerül alkalmazásra, ha [`CompressionType`](./compressiontype) CCITT4 vagy CCITT3 értékre van állítva. Olvasás/írás [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Alapértelmezett érték Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Meghatározza a tömörítés típusát. Olvasás/írás [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, amely akkor használatos, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Meghatározza a vízszintes felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Meghatározza a függőleges felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Meghatározza a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diák méretének alapján kerülnek kiszámításra. Olvasás/írás Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Lehetőségeket biztosít, amelyek szabályozzák a Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Meghatározza a generált képek pixelformatját. Olvasás/írás [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel a mentési folyamat százalékos frissítéseihez. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Lekéri vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

Az alábbi példa bemutatja, hogyan konvertálható a PowerPoint TIFF formátumba alapértelmezett mérettel.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // A prezentáció mentése TIFF dokumentumba
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Az alábbi példa bemutatja, hogyan konvertálható a PowerPoint TIFF formátumba egyéni mérettel.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Példányosítja a TiffOptions osztályt
    TiffOptions opts = new TiffOptions();
    // Tömörítési típus beállítása
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tömörítési típusok
    // Default - Az alapértelmezett tömörítési sémát (LZW) határozza meg.
    // None - Nincsen tömörítés.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // A mélység a tömörítési típustól függ, és nem állítható manuálisan.
    // A felbontási egység mindig “2” (pont per hüvelyk) értékű.
    // Kép DPI beállítása
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Kép méretének beállítása
    opts.ImageSize = new Size(1728, 1078);
    // A prezentáció mentése TIFF formátumba a megadott képmérettel
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Az alábbi példa bemutatja, hogyan konvertálható a PowerPoint TIFF formátumba egyéni képpixelformátummal.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    Az ImagePixelFormat a következő értékeket tartalmazza (a dokumentációból megtekinthető módon):
    Format1bppIndexed; // 1 bit képpontonként, indexelt.
    Format4bppIndexed; // 4 bit képpontonként, indexelt.
    Format8bppIndexed; // 8 bit képpontonként, indexelt.
    Format24bppRgb; // 24 bit képpontonként, RGB.
    Format32bppArgb; // 32 bit képpontonként, ARGB.
    */
    // A prezentáció mentése TIFF formátumba a megadott képmérettel
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ITiffOptions](../itiffoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->