---
title: SVGOptions
second_title: Aspose.Sildes dla .NET Referencja API
description: Reprezentuje opcje SVG.
type: docs
weight: 4410
url: /pl/aspose.slides.export/svgoptions/
---
## Klasa SVGOptions

Reprezentuje opcje SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicjalizuje nową instancję klasy SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicjalizuje nową instancję klasy SVGOptions, określając obiekt kontrolera osadzania linków. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Zwraca domyślne ustawienia. Tylko do odczytu [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Zwraca ustawienia dla najprostszej i najmniejszej generacji pliku SVG. Tylko do odczytu [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Zwraca ustawienia dla najbardziej dokładnej generacji pliku SVG. Tylko do odczytu [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Zwraca lub ustawia czcionkę używaną, gdy nie można znaleźć źródłowej czcionki. Odczyt/zapis String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli prawda, przycięte części zostaną usunięte, jeśli fałsz, będą serializowane w dokumencie (co może spowodować większy plik). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Określa, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na `true`, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Wyłącza podział gradientów FromCornerX i FromCenter. Odczyt/zapis Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 nie pozwala definiować wcięć dla znaczników. Silnik zapisu SVG Aspose.Slides posiada obejście tego problemu: przycina koniec linii z strzałką, aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczyt/zapis [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Określa jakość kodowania JPEG. Odczyt/zapis Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Zwraca lub ustawia dolny limit rozdzielczości dla rasteryzacji metafile. Odczyt/zapis Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Reprezentuje poziom kompresji obrazów |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje obiekt wywołania zwrotnego do zapisywania aktualizacji postępu w procentach. Zobacz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Zwraca i ustawia interfejs wywołania zwrotnego, który pozwala użytkownikowi kontrolować konwersję kształtu. Odczyt/zapis [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt/zapis Boolean. Domyślna wartość to **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Określa, czy wykonać określony obrót kształtu podczas renderowania. Odczyt/zapis Boolean. Domyślna wartość to true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania. Odczyt/zapis Boolean. Domyślna wartość to false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Zwraca lub ustawia obiekt odbierający ostrzeżenia i decydujący, czy proces ładowania będzie kontynuowany czy przerwany. Odczyt/zapis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zobacz także

* klasa [SaveOptions](../saveoptions)
* interfejs [ISVGOptions](../isvgoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->