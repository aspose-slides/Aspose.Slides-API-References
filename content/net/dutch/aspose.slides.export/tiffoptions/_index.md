---
title: TiffOptions
second_title: Aspose.Sildes voor .NET API Referentie
description: Biedt opties die regelen hoe een presentatie wordt opgeslagen in TIFF-indeling.
type: docs
weight: 4590
url: /nl/aspose.slides.export/tiffoptions/
---
## TiffOptions klasse

Biedt opties die regelen hoe een presentatie wordt opgeslagen in TIFF-indeling.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TiffOptions](tiffoptions)() | Standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Specificeert het algoritme voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [`CompressionType`](./compressiontype) is ingesteld op CCITT4 of CCITT3 Lezen/Schrijven [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Standaard is Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Specificeert het compressietype. Lezen/Schrijven [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft het lettertype terug of stelt dit in voor het geval het bronlettertype niet is gevonden. Lezen/Schrijven String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Specificeert de horizontale resolutie in dots per inch. Lezen/Schrijven UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Specificeert de verticale resolutie in dots per inch. Lezen/Schrijven UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft het visuele stijl van de gradient terug of stelt deze in. Lezen/Schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat de gegenereerde afbeeldingsgroottes worden berekend op basis van de waarde van de presentatieslidegrootte. Lezen/Schrijven Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen/Schrijven [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor om voortgangsupdates in percentage op te slaan. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lezen/Schrijven Boolean. De standaardwaarde is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voorbeelden

Het volgende voorbeeld toont hoe PowerPoint geconverteerd kan worden naar TIFF met de standaardgrootte.

```csharp
[C#]
// Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // De presentatie opslaan als TIFF-document
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Het volgende voorbeeld toont hoe PowerPoint geconverteerd kan worden naar TIFF met een aangepaste grootte.

```csharp
[C#]
// Maak een Presentation-object dat een Presentatiebestand vertegenwoordigt
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instantieer de TiffOptions-klasse
    TiffOptions opts = new TiffOptions();
    // Instellen van compressietype
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Compressietypen
    // Default - Geeft het standaard compressieschema (LZW) aan.
    // None - Geeft aan dat er geen compressie is.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Diepte hangt af van het compressietype en kan niet handmatig worden ingesteld.
    // Resolutie-eenheid is altijd gelijk aan “2” (punten per inch)
    // Instellen van afbeeldings-DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Stel afbeeldingsgrootte in
    opts.ImageSize = new Size(1728, 1078);
    // Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Het volgende voorbeeld toont hoe PowerPoint geconverteerd kan worden naar TIFF met een aangepast afbeeldingspixelformaat.

```csharp
[C#]
// Maak een Presentation-object dat een Presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat bevat de volgende waarden (zoals uit de documentatie kan worden gezien):
    Format1bppIndexed; // 1 bit per pixel, geïndexeerd.
    Format4bppIndexed; // 4 bits per pixel, geïndexeerd.
    Format8bppIndexed; // 8 bits per pixel, geïndexeerd.
    Format24bppRgb; // 24 bits per pixel, RGB.
    Format32bppArgb; // 32 bits per pixel, ARGB.
    */
    // Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* naamruimte [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->