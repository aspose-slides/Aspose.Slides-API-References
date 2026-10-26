---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions osztály

Az opciókat reprezentálja, amelyek szabályozzák, hogyan kell a prezentációt markdown formátumban menteni.

**Öröklődés:**[`MarkdownSaveOptions`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A MarkdownSaveOptions típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/__init__/#) | Konstruktor. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/warning_callback/) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/progress_callback/) | Egy visszahívási objektumot reprezentál, amely a mentés előrehaladását százalékban jelzi.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás/írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/gradient_style/) | Visszaad vagy beállít a színátmenet vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`export_type`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/export_type/) | Megadja a prezentáció konvertálásához használandó markdown specifikációt.<br/>            Alapértelmezett: `TextOnly`. |
| [`base_path`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/base_path/) | Megadja az alapútvonalat, ahová az erőforrásokat tartalmazó dokumentum mentésre kerül.<br/>            Alapértelmezett a program aktuális könyvtára. |
| [`images_save_folder_name`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Megadja a képek mentéséhez használandó mappanevet.<br/>            Alapértelmezett: `Images`. |
| [`new_line_type`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/new_line_type/) | Megadja, hogy a generált dokumentumban milyen sortöréseket használjon: \\r (Macintosh), \\n (Unix) vagy \\r\\n (Windows).<br/>            Alapértelmezett: `Unix`. |
| [`show_comments`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/show_comments/) | Megadja, hogy a generált dokumentum megjelenítse-e a megjegyzéseket.<br/>            Alapértelmezett: `false`. |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot.<br/>            Alapértelmezett: `false`. |
| [`show_slide_number`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Megadja, hogy a generált dokumentum megjelenítse-e minden dia számát.<br/>            Alapértelmezett: `false`. |
| [`flavor`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/flavor/) | Megadja a prezentáció konvertálásához használandó markdown specifikációt.<br/>            Alapértelmezett: `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Visszaad vagy beállít egy formátumkarakterláncot, amely a dia számának fejléceihez használatos a Markdown kimenetben.<br/>            A formátumnak tartalmaznia kell a "{0}" helyőrzőt, amelyet az exportálás során a dia indexével helyettesítenek.<br/>            Példa: "# Slide {0}" "# Slide 1", "# Slide 2", stb. eredményt ad. |
| [`handle_repeated_spaces`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Ha `true`-ra van állítva, eltávolítja az üres vagy csak szóközökből álló sorokat a végleges Markdown kimenetből.<br/>            Alapértelmezett: `false`. |

### Lásd még
* osztály [`MarkdownSaveOptions`](/slides/python-net/hu/aspose.slides.export/markdownsaveoptions)
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)