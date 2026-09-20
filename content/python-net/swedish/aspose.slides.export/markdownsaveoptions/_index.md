---
title: MarkdownSaveOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions klass

Representerar alternativ som styr hur presentationen ska sparas till markdown.

**Arv:**[`MarkdownSaveOptions`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

Typen MarkdownSaveOptions visar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/warning_callback/) | Returnerar eller sätter ett objekt som tar emot varningar och avgör om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/progress_callback/) | Representerar ett återuppringningsobjekt för sparande av framstegsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Returnerar eller sätter teckensnitt som används om källteckensnittet inte finns.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/gradient_style/) | Returnerar eller sätter den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. <br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`export_type`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/export_type/) | Anger markdown-specifikation för att konvertera presentationen.<br/>            Standard är `TextOnly`. |
| [`base_path`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/base_path/) | Anger grundsökvägen där dokumentet med resurser ska sparas.<br/>            Standard är applikationens nuvarande katalog. |
| [`images_save_folder_name`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Anger mappnamn för att spara bilder.<br/>            Standard är `Images`. |
| [`new_line_type`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/new_line_type/) | Anger om det genererade dokumentet ska ha radbrytningar \\r (Macintosh) \\n (Unix) eller \\r\\n (Windows).<br/>            Standard är `Unix`. |
| [`show_comments`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/show_comments/) | Anger om det genererade dokumentet ska visa kommentarer eller inte.<br/>            Standard är `false`. |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standard är `false`. |
| [`show_slide_number`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Anger om det genererade dokumentet ska visa numret på varje bild eller inte.<br/>            Standard är `false`. |
| [`flavor`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/flavor/) | Anger markdown-specifikation för att konvertera presentationen.<br/>            Standard är `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utdata.<br/>            Formatet måste inkludera platshållaren \"{0}\", som kommer att ersättas med bildens index under export.<br/>            Exempel: \"# Slide {0}\" kommer att producera \"# Slide 1\", \"# Slide 2\" osv. |
| [`handle_repeated_spaces`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Om den sätts till `true` tas tomma eller endast blanksteg innehållande rader bort från den slutliga Markdown-utdata.<br/>            Standard är `false`. |

### Se även
* klass [`MarkdownSaveOptions`](/slides/python-net/sv/aspose.slides.export/markdownsaveoptions)
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)