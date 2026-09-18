---
title: HtmlOptions class
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.export/htmloptions/
---
## HtmlOptions klasa

Reprezentuje opcje eksportu HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/pl/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ HtmlOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/pl/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Tworzy nowy obiekt HtmlOptions określający wywołanie zwrotne. |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/htmloptions/__init__/#) | Tworzy nowy obiekt HtmlOptions do zapisywania w pojedynczym pliku HTML. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/htmloptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/htmloptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/htmloptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/htmloptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/htmloptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/htmloptions/slides_layout_options/) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/htmloptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/htmloptions/show_hidden_slides/) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie.<br/>            Domyślnie `false`. |
| [`html_formatter`](/slides/python-net/pl/aspose.slides.export/htmloptions/html_formatter/) | Zwraca lub ustawia szablon HTML.<br/>            Odczyt/zapis [`IHtmlFormatter`](/slides/python-net/pl/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/pl/aspose.slides.export/htmloptions/disable_font_ligatures/) | Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur.<br/>            Gdy ustawione na `true`, ligatury będą wyłączone w renderowanym wyniku. Domyślnie właściwość jest ustawiona na `false`. |
| [`slide_image_format`](/slides/python-net/pl/aspose.slides.export/htmloptions/slide_image_format/) | Zwraca lub ustawia opcje formatu obrazu slajdu.<br/>            Odczyt/zapis [`ISlideImageFormat`](/slides/python-net/pl/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/htmloptions/jpeg_quality/) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF.<br/>            Odczyt/zapis **int**. |
| [`pictures_compression`](/slides/python-net/pl/aspose.slides.export/htmloptions/pictures_compression/) | Reprezentuje poziom kompresji obrazów |
| [`delete_pictures_cropped_areas`](/slides/python-net/pl/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli prawda, przycięte <br/>            części zostaną usunięte, jeśli fałsz, będą zserializowane w dokumencie (co może potencjalnie prowadzić do <br/>            większego pliku) |
| [`svg_responsive_layout`](/slides/python-net/pl/aspose.slides.export/htmloptions/svg_responsive_layout/) | Prawda, aby wykluczyć atrybuty width i height z kontenera svg – spowoduje to responsywny układ. Fałsz – w przeciwnym wypadku.<br/>            Odczyt/zapis **bool**. |


### Zobacz także
* klasa [`HtmlOptions`](/slides/python-net/pl/aspose.slides.export/htmloptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)