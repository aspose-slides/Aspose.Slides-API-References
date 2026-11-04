---
title: TiffOptions
second_title: Aspose.Sildes dla .NET – referencja API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.
type: docs
weight: 4590
url: /pl/aspose.slides.export/tiffoptions/
---
## Klasa TiffOptions

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktorzy

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Domyślny konstruktor. |

## Właściwości

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Określa algorytm konwertujący kolorowy obraz na czarno-biały. Ta opcja zostanie zastosowana tylko, jeśli [`CompressionType`](./compressiontype) jest ustawione na CCITT4 lub CCITT3 Odczyt/zapis [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Domyślne to Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Określa typ kompresji. Odczyt/zapis [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Zwraca lub ustawia czcionkę używaną, gdy nie odnaleziono czcionki źródłowej. Odczyt/zapis String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Określa poziomą rozdzielczość w punktach na cal. Odczyt/zapis UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Określa pionową rozdzielczość w punktach na cal. Odczyt/zapis UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Określa rozmiar generowanego obrazu TIFF. Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanego obrazu będą obliczane na podstawie rozmiaru slajdu prezentacji. Odczyt/zapis Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Określa format pikseli dla generowanych obrazów. Odczyt/zapis [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach. Zobacz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślne to `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczyt/zapis Boolean. Domyślna wartość to **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Pobiera lub ustawia tryb, w jaki slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Zwraca lub ustawia obiekt otrzymujący ostrzeżenia i decydujący, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Przykłady

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na TIFF z domyślnym rozmiarem.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Zapisywanie prezentacji do dokumentu TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na TIFF z niestandardowym rozmiarem.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Utwórz obiekt klasy TiffOptions
    TiffOptions opts = new TiffOptions();
    // Ustawianie typu kompresji
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Typy kompresji
    // Default - Określa domyślny schemat kompresji (LZW).
    // None - Określa brak kompresji.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Głębia zależy od typu kompresji i nie może być ustawiona ręcznie.
    // Jednostka rozdzielczości  jest zawsze równa „2” (punkty na cal)
    // Ustawianie DPI obrazu
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Ustaw rozmiar obrazu
    opts.ImageSize = new Size(1728, 1078);
    // Zapisz prezentację jako TIFF z określonym rozmiarem obrazu
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na TIFF z niestandardowym formatem piksela obrazu.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat zawiera następujące wartości (zgodnie z dokumentacją):
    Format1bppIndexed; // 1 bit na piksel, indeksowany.
    Format4bppIndexed; // 4 bity na piksel, indeksowany.
    Format8bppIndexed; // 8 bitów na piksel, indeksowany.
    Format24bppRgb; // 24 bity na piksel, RGB.
    Format32bppArgb; // 32 bity na piksel, ARGB.
    */
    // Zapisz prezentację jako TIFF z określonym rozmiarem obrazu
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Zobacz także

* klasa [SaveOptions](../saveoptions)
* interfejs [ITiffOptions](../itiffoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->