---
title: TiffOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
type: docs
weight: 4590
url: /sv/aspose.slides.export/tiffoptions/
---
## TiffOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions)() | Standardkonstruktor. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ tillämpas endast om [`CompressionType`](./compressiontype) är inställt på CCITT4 eller CCITT3 Läs/skriv [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Standard är Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Specificerar kompressionstypen. Läs/skriv [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returnerar eller anger teckensnitt som används om källteckensnittet inte finns. Läs/skriv String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Specificerar horisontell upplösning i punkter per tum. Läs/skriv UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Specificerar vertikal upplösning i punkter per tum. Läs/skriv UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Specificerar storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att genererade bildstorlekar beräknas baserat på presentationens bildstorlek. Läs/skriv Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterade dokument. Läs-endast [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Specificerar pixelformatet för de genererade bilderna. Läs/skriv [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Specificerar om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificerar om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs/skriv Boolean. Standardvärdet är **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returnerar eller anger ett objekt som mottar varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exempel

Följande exempel visar hur man konverterar PowerPoint till TIFF med standardstorlek.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en presentationsfil
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Sparar presentationen till TIFF-dokument
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassad storlek.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en Presentation-fil
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instansiera TiffOptions-klassen
    TiffOptions opts = new TiffOptions();
    // Ställer in komprimeringstypen
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Komprimeringstyper
    // Default - Anger standardkomprimeringsschemat (LZW).
    // None - Anger ingen komprimering.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Djup beror på komprimeringstypen och kan inte ställas in manuellt.
    // Upplösningsenheten  är alltid lika med “2” (dots per inch)
    // Ställer in bildens DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Ställ in bildstorlek
    opts.ImageSize = new Size(1728, 1078);
    // Spara presentationen till TIFF med angiven bildstorlek
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassat bildpixelformat.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en Presentation-fil
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat innehåller följande värden (som kan ses i dokumentationen):
    Format1bppIndexed; // 1 bit per pixel, indexerad.
    Format4bppIndexed; // 4 bitar per pixel, indexerad.
    Format8bppIndexed; // 8 bitar per pixel, indexerad.
    Format24bppRgb; // 24 bitar per pixel, RGB.
    Format32bppArgb; // 32 bitar per pixel, ARGB.
    */
    // Spara presentationen till TIFF med angiven bildstorlek
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Se också

* klass [SaveOptions](../saveoptions)
* gränssnitt [ITiffOptions](../itiffoptions)
* namnrymd [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->