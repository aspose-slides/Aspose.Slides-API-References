---
title: SwfOptions class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.export/swfoptions/
---
## Klasa SwfOptions

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie Swf.

**Inheritance:**[`SwfOptions`](/slides/python-net/pl/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ SwfOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/swfoptions/__init__/#) | Domyślny konstruktor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/swfoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/swfoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego służący do aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/swfoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną w przypadku nieznalezienia czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/swfoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/swfoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie.<br/>            Domyślnie `false`. |
| [`compressed`](/slides/python-net/pl/aspose.slides.export/swfoptions/compressed/) | Określa, czy wygenerowany dokument SWF ma być skompresowany, czy nie.<br/>            Domyślnie `true`. |
| [`viewer_included`](/slides/python-net/pl/aspose.slides.export/swfoptions/viewer_included/) | Określa, czy wygenerowany dokument SWF ma zawierać wbudowany przeglądnik dokumentów, czy nie.<br/>            Domyślnie `true`. |
| [`show_page_border`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_page_border/) | Określa, czy ma być wyświetlana ramka wokół stron. Domyślnie true. |
| [`show_full_screen`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_full_screen/) | Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true. |
| [`show_page_stepper`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_page_stepper/) | Pokaż/ukryj przełącznik stron. Może być nadpisane w flashvars. Domyślnie true. |
| [`show_search`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_search/) | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| [`show_top_pane`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_top_pane/) | Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| [`show_bottom_pane`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_bottom_pane/) | Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| [`show_left_pane`](/slides/python-net/pl/aspose.slides.export/swfoptions/show_left_pane/) | Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| [`start_open_left_pane`](/slides/python-net/pl/aspose.slides.export/swfoptions/start_open_left_pane/) | Rozpocznij z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| [`enable_context_menu`](/slides/python-net/pl/aspose.slides.export/swfoptions/enable_context_menu/) | Włącz/wyłącz menu kontekstowe. Domyślnie true. |
| [`logo_image_bytes`](/slides/python-net/pl/aspose.slides.export/swfoptions/logo_image_bytes/) | Obraz, który zostanie wyświetlony jako logo w prawym górnym rogu przeglądarki.<br/>            Obraz powinien mieć rozmiar 32x64 pikseli i format PNG, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| [`logo_link`](/slides/python-net/pl/aspose.slides.export/swfoptions/logo_link/) | Zwraca lub ustawia pełny adres hiperłącza dla logo.<br/>            Ma efekt tylko, jeśli określono [`SwfOptions.logo_image_bytes`](/slides/python-net/pl/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/swfoptions/jpeg_quality/) | Określa jakość obrazów JPEG.<br/>            Domyślnie 95. |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/swfoptions/slides_layout_options/) | Zwraca lub ustawia tryb, w jakim slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions).<br/>            Ta właściwość nie obsługuje przypisywania obiektów typu [`HandoutLayoutingOptions`](/slides/python-net/pl/aspose.slides.export/handoutlayoutingoptions) |

### Zobacz także
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* klasa [`SwfOptions`](/slides/python-net/pl/aspose.slides.export/swfoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)