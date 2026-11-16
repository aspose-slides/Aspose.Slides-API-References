---
title: TiffOptions
second_title: Aspose.Sildes a .NET API Referenciához
description: Lehetővé teszi a beállítások megadását, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.
type: docs
weight: 4590
url: /hu/aspose.slides.export/tiffoptions/
---
## TiffOptions osztály

Provides options that control how a presentation is saved in TIFF format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Megadja a színes kép fekete-fehér képpé alakításához használt algoritmust. Ez az opció csak akkor lesz alkalmazva, ha [`CompressionType`](./compressiontype) CCITT4 vagy CCITT3 értékre van beállítva. Olvasás/írás [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Default is Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Megadja a tömörítés típusát. Olvasás/írás [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a forrás betűtípus hiányában használt betűtípust. Olvasás/írás String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Megadja a generált TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diák mérete alapján lesznek kiszámítva. Olvasás/írás Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Biztosítja a beágyazott objektumok megjelenését szabályozó beállításokat az exportált dokumentumban. Csak olvasás [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Megadja a generált képek pixel formátumát. Olvasás/írás [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Képviseli a mentés előrehaladásának százalékos frissítéseit kezelő visszahívási objektumot. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyeződnek egy prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad-e. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

A következő példa bemutatja, hogyan konvertáljuk a PowerPointot TIFF formátumba alapértelmezett mérettel.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // A prezentáció mentése TIFF dokumentumba
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

A következő példa bemutatja, hogyan konvertáljuk a PowerPointot TIFF formátumba egyéni mérettel.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy Presentation fájlt képvisel
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
    // Default - A alapértelmezett tömörítési sémát határozza meg (LZW).
    // None - Nem használ tömörítést.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // A mélység a tömörítési típustól függ, és nem állítható manuálisan.
    // A felbontási egység mindig „2” (pont per hüvelyk).
    // Kép DPI beállítása
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Kép méretének beállítása
    opts.ImageSize = new Size(1728, 1078);
    // A prezentáció mentése TIFF formátumba a megadott kép mérettel
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

A következő példa bemutatja, hogyan konvertáljuk a PowerPointot TIFF formátumba egyéni képpont formátummal.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy Presentation fájlt képvisel
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat a következő értékeket tartalmazza (a dokumentációból látható módon):
    Format1bppIndexed; // 1 bit per pixel, indexelt.
    Format4bppIndexed; // 4 bit per pixel, indexelt.
    Format8bppIndexed; // 8 bit per pixel, indexelt.
    Format24bppRgb; // 24 bit per pixel, RGB.
    Format32bppArgb; // 32 bit per pixel, ARGB.
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