---
title: MarkdownSaveOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions klasse

Stelt opties voor die bepalen hoe een presentatie moet worden opgeslagen als markdown.

**Erfenis:**[`MarkdownSaveOptions`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

Het type MarkdownSaveOptions exposeert de volgende leden:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/warning_callback/) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt geannuleerd.<br/>            Lezen/Schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/progress_callback/) | Stelt een callback-object voor om voortgangsupdates bij het opslaan in percentage weer te geven.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/gradient_style/) | Retourneert of stelt de visuele stijl van de gradient in.<br/>            Lezen/Schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. <br/>            Lezen/Schrijven **bool**. De standaardwaarde is **false**. |
| [`export_type`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/export_type/) | Specificeert de markdown-specificatie om de presentatie te converteren.<br/>            Standaard is `TextOnly`. |
| [`base_path`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/base_path/) | Specificeert het basispad waar het document met bronnen wordt opgeslagen.<br/>            Standaard is de huidige map van de applicatie. |
| [`images_save_folder_name`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Specificeert de mapnaam om afbeeldingen op te slaan.<br/>            Standaard is `Images`. |
| [`new_line_type`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/new_line_type/) | Specificeert of het gegenereerde document nieuwe regels \\r (Macintosh), \\n (Unix) of \\r\\n (Windows) moet hebben.<br/>            Standaard is `Unix`. |
| [`show_comments`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/show_comments/) | Specificeert of het gegenereerde document opmerkingen moet weergeven of niet.<br/>            Standaard is `false`. |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet opnemen of niet.<br/>            Standaard is `false`. |
| [`show_slide_number`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Specificeert of het tegenereerde document het nummer van elke dia moet weergeven of niet.<br/>            Standaard is `false`. |
| [`flavor`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/flavor/) | Specificeert de markdown-specificatie om de presentatie te converteren.<br/>            Standaard is `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Verkrijgt of stelt de opmaak-string in die wordt gebruikt voor dia-nummerkoppen in Markdown-output.<br/>            Het formaat moet de \"{0}\"-plaatsaanduiding bevatten, die tijdens de export wordt vervangen door de dia-index.<br/>            Voorbeeld: \"# Slide {0}\" resulteert in \"# Slide 1\", \"# Slide 2\", enz. |
| [`handle_repeated_spaces`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Indien ingesteld op `true`, worden lege of alleen uit witruimte bestaande regels uit de uiteindelijke Markdown-output verwijderd.<br/>            Standaard is `false`. |

### Zie ook
* klasse [`MarkdownSaveOptions`](/slides/python-net/nl/aspose.slides.export/markdownsaveoptions)
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)