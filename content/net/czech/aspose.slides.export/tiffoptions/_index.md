---
title: TiffOptions
second_title: Aspose.Sildes pro .NET API reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.
type: docs
weight: 4570
url: /cs/aspose.slides.export/tiffoptions/
---
## TiffOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [TiffOptions](tiffoptions)() | Výchozí konstruktor. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba se použije pouze pokud je [`CompressionType`](./compressiontype) nastaven na CCITT4 nebo CCITT3 Čtení/zápis [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Výchozí je Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Určuje typ komprese. Čtení/zápis [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že výchozí písmo není nalezeno. Čtení/zápis String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Určuje horizontální rozlišení v bodech na palec. Čtení/zápis UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Určuje vertikální rozlišení v bodech na palec. Čtení/zápis UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Určuje velikost vygenerovaného TIFF obrázku. Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaného obrázku budou vypočítány na základě velikosti snímku prezentace. Čtení/zápis Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze ke čtení [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Určuje formát pixelů pro vygenerované obrázky. Čtení/zápis [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky nebo ne. Výchozí hodnota je `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Příklady

Následující příklad ukazuje, jak převést PowerPoint do TIFF s výchozí velikostí.

```csharp
[C#]
// Vytvořte objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Uložení prezentace do TIFF dokumentu
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Následující příklad ukazuje, jak převést PowerPoint do TIFF se vlastní velikostí.

```csharp
[C#]
// Vytvořte objekt Presentation, který představuje soubor prezentace
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Vytvořte instanci třídy TiffOptions
    TiffOptions opts = new TiffOptions();
    // Nastavení typu komprese
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Typy komprese
    // Default - Určuje výchozí schéma komprese (LZW).
    // None - Určuje žádnou kompresi.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Hloubka závisí na typu komprese a nelze ji nastavit ručně.
    // Resolution unit  je vždy rovna "2" (bodů na palec)
    // Nastavení DPI obrázku
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Nastavte velikost obrázku
    opts.ImageSize = new Size(1728, 1078);
    // Uložte prezentaci do TIFF s určenou velikostí obrázku
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Následující příklad ukazuje, jak převést PowerPoint do TIFF s vlastním formátem pixelů obrázku.

```csharp
[C#]
// Vytvořte objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat obsahuje následující hodnoty (jak je vidět v dokumentaci):
    Format1bppIndexed; // 1 bit na pixel, indexováno.
    Format4bppIndexed; // 4 bity na pixel, indexováno.
    Format8bppIndexed; // 8 bitů na pixel, indexováno.
    Format24bppRgb; // 24 bitů na pixel, RGB.
    Format32bppArgb; // 32 bitů na pixel, ARGB.
    */
    // Uložte prezentaci do TIFF s určenou velikostí obrázku
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [ITiffOptions](../itiffoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->