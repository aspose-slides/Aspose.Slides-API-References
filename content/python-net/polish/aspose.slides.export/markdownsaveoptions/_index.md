---
title: MarkdownSaveOptions class
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions klasa

Reprezentuje opcje kontrolujące sposób zapisywania prezentacji do formatu markdown.

**Dziedziczenie:**[`MarkdownSaveOptions`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ MarkdownSaveOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/__init__/#) | Konstruktor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces wczytywania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie odnaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`export_type`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/export_type/) | Określa specyfikację markdown używaną do konwersji prezentacji.<br/>            Domyślnie `TextOnly`. |
| [`base_path`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/base_path/) | Określa podstawową ścieżkę, w której zostanie zapisany dokument wraz z zasobami.<br/>            Domyślnie jest to bieżący katalog aplikacji. |
| [`images_save_folder_name`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Określa nazwę folderu, w którym będą zapisywane obrazy.<br/>            Domyślnie `Images`. |
| [`new_line_type`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/new_line_type/) | Określa, czy wygenerowany dokument ma mieć nowe linie \\r(Macintosh), \\n(Unix) lub \\r\\n(Windows).<br/>            Domyślnie `Unix`. |
| [`show_comments`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/show_comments/) | Określa, czy wygenerowany dokument ma wyświetlać komentarze.<br/>            Domyślnie `false`. |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy.<br/>            Domyślnie `false`. |
| [`show_slide_number`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Określa, czy wygenerowany dokument ma wyświetlać numer każdego slajdu.<br/>            Domyślnie `false`. |
| [`flavor`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/flavor/) | Określa specyfikację markdown używaną do konwersji prezentacji.<br/>            Domyślnie `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Zwraca lub ustawia ciąg formatowania używany dla nagłówków numerów slajdów w wyjściu Markdown.<br/>            Format musi zawierać placeholder \"{0}\", który zostanie zastąpiony indeksem slajdu podczas eksportu.<br/>            Przykład: \"# Slide {0}\" wygeneruje \"# Slide 1\", \"# Slide 2\" itd. |
| [`handle_repeated_spaces`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Jeśli ustawiono na `true`, usuwa puste lub zawierające wyłącznie białe znaki wiersze z ostatecznego wyjścia Markdown.<br/>            Domyślnie `false`. |

### Zobacz też
* klasa [`MarkdownSaveOptions`](/slides/python-net/pl/aspose.slides.export/markdownsaveoptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)