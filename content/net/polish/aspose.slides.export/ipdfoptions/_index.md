---
title: IPdfOptions
second_title: Aspose.Sildes dla .NET Odniesienie do API
description: Udostępnia opcje kontrolujące, jak prezentacja jest zapisywana w formacie Pdf.
type: docs
weight: 4020
url: /pl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfejs

Udostępnia opcje kontrolujące, jak prezentacja jest zapisywana w formacie Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien traktować jako wspólne. Odczyt/zapis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Stosuje określony przezroczysty kolor do obrazu, jeśli `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Zwraca interfejs ISaveOptions. Tylko do odczytu [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Wskazuje, czy dla każdego obrazu ma być automatycznie wybierana najskuteczniejsza kompresja (zamiast domyślnej). Jeśli ustawiono na Boolean.true, dla każdego obrazu w prezentacji zostanie wybrany najodpowiedniejszy algorytm kompresji, co spowoduje mniejszy rozmiar wygenerowanego dokumentu PDF. Wybór najlepszej proporcji kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a domyślnie opcja ta ma wartość Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Pożądany poziom zgodności generowanego dokumentu PDF. Odczyt/zapis [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko użyty podzbiór. Odczyt/zapis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, aby osadzić czcionki TrueType dla znaków ASCII 32-127. Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Odczyt/zapis Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wygenerowanym PDF. Odczyt/zapis Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Ustawienie hasła użytkownika chroniącego dokument PDF. Odczyt/zapis String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Wskazuje, czy tekst powinien być rastrowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje stylu pogrubionego. To podejście może poprawić jakość tekstu w wygenerowanym PDF dla niektórych czcionek. Odczyt/zapis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, aby przekonwertować wszystkie pliki metafile używane w prezentacji na obrazy PNG. Odczyt/zapis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [`PdfTextCompression`](../pdftextcompression). |

### Zobacz także

* interfejs [ISaveOptions](../isaveoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->