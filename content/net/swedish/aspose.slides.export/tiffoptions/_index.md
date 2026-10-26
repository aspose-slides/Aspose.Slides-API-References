---
title: TiffOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
type: docs
weight: 4570
url: /sv/aspose.slides.export/tiffoptions/
---
## TiffOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions)() | Standardkonstruktor. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Anger algoritmen för att konvertera en färgbild till en svart-vit bild. Detta alternativ tillämpas endast om [`CompressionType`](./compressiontype) är inställt på CCITT4 eller CCITT3 Läs/skriv [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Standard är Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Anger komprimeringstypen. Läs/skriv [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returnerar eller ställer in teckensnittet som används om källteckensnittet inte hittas. Läs/skriv String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Anger horisontell upplösning i punkter per tum. Läs/skriv UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Anger vertikal upplösning i punkter per tum. Läs/skriv UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returnerar eller ställer in den visuella stilen för gradienten. Läs/skriv [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Anger storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att bildstorlekarna beräknas utifrån presentationens bildsidors storlek. Läs/skriv Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. Endast läsning [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Anger pixelformaten för de genererade bilderna. Läs/skriv [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representerar ett återuppringningsobjekt för att spara förloppsuppdateringar i procent. Se [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Läs/skriv Boolean. Standardvärdet är **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Hämtar eller ställer in läget i vilket bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returnerar eller ställer in ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exempel

Följande exempel visar hur man konverterar PowerPoint till TIFF med standardstorlek.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en presentationsfil
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Sparar presentationen till ett TIFF-dokument
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassad storlek.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en presentationsfil
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instansiera TiffOptions-klassen
    TiffOptions opts = new TiffOptions();
    // Ställer in komprimeringstyp
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Komprimeringstyper
    // Default - Anger det förvalda komprimeringsschemat (LZW).
    // None - Anger ingen kompression.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Djup beror på komprimeringstypen och kan inte ställas in manuellt.
    // Upplösningsenhet  är alltid lika med “2” (punkter per tum)
    // Ställer in bild-DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Ställ in bildstorlek
    opts.ImageSize = new Size(1728, 1078);
    // Spara presentationen som TIFF med angiven bildstorlek
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassat bildpixelformat.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en presentationsfil
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

### Se även

* klass [SaveOptions](../saveoptions)
* gränssnitt [ITiffOptions](../itiffoptions)
* namnrymd [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->