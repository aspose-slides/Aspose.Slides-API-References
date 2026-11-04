---
title: SwfOptions
second_title: Aspose.Sildes dla .NET API Reference
description: Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie Swf.
type: docs
weight: 4550
url: /pl/aspose.slides.export/swfoptions/
---
## SwfOptions klasa

Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [SwfOptions](swfoptions)() | Konstruktor domyślny. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Określa, czy wygenerowany dokument SWF powinien być kompresowany, czy nie. Domyślnie `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie odnaleziono czcionki źródłowej. Odczyt/zapis String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Włącza/wyłącza menu kontekstowe. Domyślnie true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Określa jakość obrazów JPEG. Domyślnie 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien mieć wymiary 32x64 pikseli w formacie PNG, w przeciwnym razie logo może być wyświetlane nieprawidłowo. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Zwraca lub ustawia pełny adres hiperłącza dla logo. Ma wpływ tylko wtedy, gdy określono [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje obiekt zwrotnego wywołania do zapisywania aktualizacji postępu w procentach. Zobacz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Pokaż/ukryj dolny panel. Może być nadpisany w flashvars. Domyślnie true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisany w flashvars. Domyślnie true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Pokaż/ukryj lewy panel. Może być nadpisany w flashvars. Domyślnie true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Określa, czy ma być wyświetlana ramka wokół stron. Domyślnie true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Pokaż/ukryj przełącznik stron. Może być nadpisany w flashvars. Domyślnie true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisany w flashvars. Domyślnie true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Pokaż/ukryj cały górny panel. Może być nadpisany w flashvars. Domyślnie true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczyt/zapis Boolean. Domyślna wartość to **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [`ISlidesLayoutOptions`](../islideslayoutoptions). Ta właściwość nie obsługuje przypisywania obiektów typu [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Rozpocznij z otwartym lewym panelem. Może być nadpisany w flashvars. Domyślnie false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowaną przeglądarkę dokumentów, czy nie. Domyślnie `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Przykłady

Poniższy przykład pokazuje, jak konwertować PowerPoint do Flash SWF.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Zapisywanie prezentacji i stron notatek
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Zobacz także

* klasa [SaveOptions](../saveoptions)
* interfejs [ISwfOptions](../iswfoptions)
* przestrzeń nazw [Aspose.Slides.Export](../../aspose.slides.export)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->