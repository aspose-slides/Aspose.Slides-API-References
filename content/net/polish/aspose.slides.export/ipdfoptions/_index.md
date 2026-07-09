---
title: IPdfOptions
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.
type: docs
weight: 4000
url: /pl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfejs

Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie PDF.

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
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Określa, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawiona na Boolean.true, dla każdego obrazu w prezentacji zostanie wybrany najodpowiedniejszy algorytm kompresji, co doprowadzi do mniejszego rozmiaru wynikowego dokumentu PDF. Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a domyślnie ta opcja ma wartość Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Pożądany poziom zgodności generowanego dokumentu PDF. Odczyt/zapis [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Określa, czy wszystkie znaki czcionki powinny być osadzone, czy tylko używany podzbiór. Odczyt/zapis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, aby osadzić czcionki TrueType dla znaków ASCII 32-127. Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Odczyt/zapis Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Zwraca lub ustawia przezroczysty kolor obrazu. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt/zapis Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. Odczyt/zapis String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Określa, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek. Odczyt/zapis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, aby przekonwertować wszystkie metaplikiety użyte w prezentacji na obrazy PNG. Odczyt/zapis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie jest `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Zwraca lub ustawia tryb, w jakim slajdy są rozmieszczane na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [`PdfTextCompression`](../pdftextcompression). |

### Zobacz także

* interfejs [ISaveOptions](../isaveoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->