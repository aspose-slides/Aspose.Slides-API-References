---
title: PdfOptions
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.
type: docs
weight: 4310
url: /pl/aspose.slides.export/pdfoptions/
---
## klasa PdfOptions

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [PdfOptions](pdfoptions)() | Konstruktor domyślny. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane, gdy dokument jest otwierany z dostępem użytkownika. Zobacz [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. Odczyt/zapis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Zastosowuje określony przezroczysty kolor do obrazu, jeśli `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawiono na Boolean.true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co doprowadzi do mniejszego rozmiaru wynikowego dokumentu PDF. Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a opcja ta ma wartość Boolean.false domyślnie. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Żądany poziom zgodności generowanego dokumentu PDF. Odczyt/zapis [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Prawda, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko użyty podzbiór. Odczyt/zapis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127). Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Lista czcionek wspólnych obejmuje bazowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika. Odczyt/zapis Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Zwraca lub ustawia wizualny styl gradientu. Odczyt/zapis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Prawda, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt/zapis Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Ustawia hasło użytkownika chroniące dokument PDF. Odczyt/zapis String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach. Zobacz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Wskazuje, czy tekst powinien być rastrowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje stylu pogrubionego. To podejście może zwiększyć jakość tekstu w wygenerowanym PDF dla niektórych czcionek. Odczyt/zapis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Prawda, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt/zapis Boolean. Wartość domyślna to **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Określa typ kompresji używany dla całej zawartości tekstowej w dokumencie. Odczyt/zapis [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Przykłady

Poniższy przykład pokazuje, jak przekonwertować PowerPoint do PDF z niestandardowymi opcjami.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Tworzy instancję klasy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ustawia jakość JPEG
	pdfOptions.JpegQuality = 90;
	// Ustawia zachowanie metafili
	pdfOptions.SaveMetafilesAsPng = true;
	// Ustawia poziom kompresji tekstu
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definiuje standard PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Zapisuje prezentację jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Poniższy przykład pokazuje, jak przekonwertować PowerPoint do PDF z ukrytymi slajdami.

```csharp
[C#]
// Tworzy instancję klasy Presentation, która reprezentuje plik PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Tworzy instancję klasy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Dodaje ukryte slajdy
	pdfOptions.ShowHiddenSlides = true;
	// Zapisuje prezentację jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Poniższy przykład pokazuje, jak przekonwertować PowerPoint do PDF zabezpieczonego hasłem.

```csharp
[C#]
// Tworzy obiekt Presentation, który reprezentuje plik PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Tworzy instancję klasy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ustawia hasło PDF i uprawnienia dostępu
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Zapisuje prezentację jako PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Poniższy przykład pokazuje, jak przekonwertować PowerPoint do PDF z notatkami.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Ustawianie typu i rozmiaru slajdu
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Zobacz także

* klasa [SaveOptions](../saveoptions)
* interfejs [IPdfOptions](../ipdfoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->