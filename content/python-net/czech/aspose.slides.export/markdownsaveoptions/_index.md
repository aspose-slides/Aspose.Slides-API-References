---
title: MarkdownSaveOptions class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions třída

Představuje možnosti, které řídí, jak má být prezentace uložena do markdownu.

**Dědičnost:**[`MarkdownSaveOptions`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ MarkdownSaveOptions poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/__init__/#) | Konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen.<br/>            Čtení/zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/progress_callback/) | Representuje zpětné volání pro aktualizace postupu ukládání v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Vrací nebo nastavuje font použitý v případě, že není nalezen zdrojový font.<br/>            Čtení/zápis **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Čtení/zápis [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Čtení/zápis **bool**. Výchozí hodnota je **false**. |
| [`export_type`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/export_type/) | Určuje markdown specifikaci pro převod prezentace.<br/>            Výchozí je `TextOnly`. |
| [`base_path`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/base_path/) | Určuje základní cestu, kde bude dokument s prostředky uložen.<br/>            Výchozí je aktuální adresář aplikace. |
| [`images_save_folder_name`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Určuje název složky pro ukládání obrázků.<br/>            Výchozí je `Images`. |
| [`new_line_type`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/new_line_type/) | Určuje, zda má vygenerovaný dokument mít nové řádky \\r(Macintosh) nebo \\n(Unix) nebo \\r\\n(Windows).<br/>            Výchozí je `Unix`. |
| [`show_comments`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/show_comments/) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře nebo ne.<br/>            Výchozí je `false`. |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky nebo ne.<br/>            Výchozí je `false`. |
| [`show_slide_number`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku nebo ne.<br/>            Výchozí je `false`. |
| [`flavor`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/flavor/) | Určuje markdown specifikaci pro převod prezentace.<br/>            Výchozí je `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Vrací nebo nastavuje řetězec formátu používaný pro záhlaví číslování snímků ve výstupu Markdown.<br/>            Formát musí obsahovat zástupný znak \"{0}\", který bude během exportu nahrazen indexem snímku.<br/>            Příklad: \"# Slide {0}\" vytvoří \"# Slide 1\", \"# Slide 2\" atd. |
| [`handle_repeated_spaces`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Pokud je nastaveno na `true`, odstraní prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown.<br/>            Výchozí je `false`. |

### Viz také
* třída [`MarkdownSaveOptions`](/slides/python-net/cs/aspose.slides.export/markdownsaveoptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)