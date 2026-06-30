---
title: TiffOptions
second_title: Aspose.Sildes .NET API Referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció TIFF formátumban.
type: docs
weight: 4550
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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Megadja a színes kép fekete-fehér képpé konvertálásához használt algoritmust. Ez a beállítás csak akkor alkalmazandó, ha [`CompressionType`](./compressiontype) CCITT4 vagy CCITT3 értékre van állítva. Olvasás/írás [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Alapértelmezett a Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Megadja a tömörítés típusát. Olvasás/írás [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűkészletet, ha a forrás betűkészlet nem található. Olvasás/írás String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Megadja egy generált TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diamérete alapján kerülnek kiszámításra. Olvasás/írás Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Lehetőségeket biztosít, amelyek szabályozzák az exportált dokumentumban lévő Ink objektumok megjelenését. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Megadja a pixel formátumot a generált képekhez. Olvasás/írás [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot reprezentál, amely a mentés előrehaladását százalékban jelzi. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat. Alapértelmezett a `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Megadja vagy beállítja a módot, ahogyan a diák az oldalon elhelyeződnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaad egy objektumot vagy állít be egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

A következő példa bemutatja, hogyan konvertálhatja a PowerPointot TIFF-re alapértelmezett mérettel.

```csharp
[C#]
// Egy Presentation objektum példányosítása, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // A prezentáció mentése TIFF dokumentumba
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

A következő példa bemutatja, hogyan konvertálhatja a PowerPointot TIFF-re egyéni mérettel.

```csharp
[C#]
// Egy Presentation objektum példányosítása, amely egy prezentációs fájlt képvisel
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // A TiffOptions osztály példányosítása
    TiffOptions opts = new TiffOptions();
    // A tömörítési típus beállítása
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tömörítési típusok
    // Default - A alapértelmezett tömörítési sémát (LZW) határozza meg.
    // None - Nem alkalmaz tömörítést.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // A mélység a tömörítési típustól függ, és nem állítható be manuálisan.
    // A felbontási egység mindig „2” (pont per hüvelyk) értékű.
    // Kép DPI beállítása
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Képméret beállítása
    opts.ImageSize = new Size(1728, 1078);
    // A prezentáció mentése TIFF-be a megadott képmérettel
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

A következő példa bemutatja, hogyan konvertálhatja a PowerPointot TIFF-re egyéni képpixel formátummal.

```csharp
[C#]
// Egy Presentation objektum példányosítása, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    Az ImagePixelFormat a következő értékeket tartalmazza (a dokumentációból látható módon):
    Format1bppIndexed; // 1 bit per pixel, indexelt.
    Format4bppIndexed; // 4 bit per pixel, indexelt.
    Format8bppIndexed; // 8 bit per pixel, indexelt.
    Format24bppRgb; // 24 bit per pixel, RGB.
    Format32bppArgb; // 32 bit per pixel, ARGB.
    */
    // A prezentáció mentése TIFF-be a megadott képmérettel
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ITiffOptions](../itiffoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->