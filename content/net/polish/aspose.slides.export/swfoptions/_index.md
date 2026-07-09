---
title: SwfOptions
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Zapewnia opcje kontrolujące sposób zapisywania prezentacji w formacie Swf.
type: docs
weight: 4530
url: /pl/aspose.slides.export/swfoptions/
---
## SwfOptions klasa

Zapewnia opcje kontrolujące sposób zapisywania prezentacji w formacie Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [SwfOptions](swfoptions)() | Domyślny konstruktor. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Określa, czy wygenerowany dokument SWF powinien być kompresowany, czy nie. Domyślnie jest `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie odnaleziono czcionki źródłowej. Odczyt-zapis String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Włącza/wyłącza menu kontekstowe. Domyślnie jest true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Określa jakość obrazów JPEG. Domyślnie 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien mieć 32x64 piksele w formacie PNG, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Zwraca lub ustawia pełny adres hiperłącza dla logo. Ma wpływ tylko wtedy, gdy określono [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach. Zobacz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Wyświetla/ukrywa dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Wyświetla/ukrywa przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy. Domyślnie `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Wyświetla/ukrywa lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Określa, czy ma być wyświetlana ramka wokół stron. Domyślnie true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Wyświetla/ukrywa kontrolkę przechodzenia pomiędzy stronami. Może być nadpisane w flashvars. Domyślnie true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Wyświetla/ukrywa sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Wyświetla/ukrywa cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt/zapis Boolean. Domyślna wartość to **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Zwraca lub ustawia tryb układania slajdów na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). Ta właściwość nie obsługuje przypisywania obiektów typu [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Rozpoczyna z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Określa, czy wygenerowany dokument SWF powinien zawierać zintegrowaną przeglądarkę dokumentów. Domyślnie `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczyt/zapis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Przykłady

Poniższy przykład pokazuje, jak przekonwertować PowerPoint do SWF Flash.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Zapis prezentacji i stron notatek
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Zobacz także

* klasa [SaveOptions](../saveoptions)
* interfejs [ISwfOptions](../iswfoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zasób [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->