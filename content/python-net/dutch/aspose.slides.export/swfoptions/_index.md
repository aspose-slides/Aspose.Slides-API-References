---
title: SwfOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/swfoptions/
---
## SwfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-indeling.

**Erfenis:**[`SwfOptions`](/slides/python-net/nl/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

Het type SwfOptions maakt de volgende leden beschikbaar:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/swfoptions/__init__/#) | Standaardconstructor. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/swfoptions/warning_callback/) | Geeft of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken.<br/>            Lezen/Schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/swfoptions/progress_callback/) | Stelt een callback-object voor voor het opslaan van voortgangsupdates in percentage.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/swfoptions/default_regular_font/) | Geeft of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/swfoptions/gradient_style/) | Geeft of stelt de visuele stijl van de verlopen in.<br/>            Lezen/Schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/swfoptions/skip_java_script_links/) | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie.<br/>            Lezen/Schrijven **bool**. De standaardwaarde is **false**. |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`compressed`](/slides/python-net/nl/aspose.slides.export/swfoptions/compressed/) | Specificeert of het gegenereerde SWF-document gecomprimeerd moet worden of niet.<br/>            Standaard is `true`. |
| [`viewer_included`](/slides/python-net/nl/aspose.slides.export/swfoptions/viewer_included/) | Specificeert of het tegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet.<br/>            Standaard is `true`. |
| [`show_page_border`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_page_border/) | Specificeert of een rand rond pagina's moet worden weergegeven. Standaard is true. |
| [`show_full_screen`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_full_screen/) | Toon/verberg fullscreen-knop. Kan worden overschreven in flashvars. Standaard is true. |
| [`show_page_stepper`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_page_stepper/) | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| [`show_search`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_search/) | Toon/verberg zoekgedeelte. Kan worden overschreven in flashvars. Standaard is true. |
| [`show_top_pane`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_top_pane/) | Toon/verberg hele bovenste paneel. Kan worden overschreven in flashvars. Standaard is true. |
| [`show_bottom_pane`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_bottom_pane/) | Toon/verberg onderste paneel. Kan worden overschreven in flashvars. Standaard is true. |
| [`show_left_pane`](/slides/python-net/nl/aspose.slides.export/swfoptions/show_left_pane/) | Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true. |
| [`start_open_left_pane`](/slides/python-net/nl/aspose.slides.export/swfoptions/start_open_left_pane/) | Start met geopend linker paneel. Kan worden overschreven in flashvars. Standaard is false. |
| [`enable_context_menu`](/slides/python-net/nl/aspose.slides.export/swfoptions/enable_context_menu/) | Inschakelen/uitschakelen contextmenu. Standaard is true. |
| [`logo_image_bytes`](/slides/python-net/nl/aspose.slides.export/swfoptions/logo_image_bytes/) | Afbeelding die wordt weergegeven als logo in de rechterbovenhoek van de viewer.<br/>            De afbeelding moet een PNG-afbeelding van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| [`logo_link`](/slides/python-net/nl/aspose.slides.export/swfoptions/logo_link/) | Geeft of stelt het volledige hyperlink-adres voor een logo in.<br/>            Heeft alleen effect als een [`SwfOptions.logo_image_bytes`](/slides/python-net/nl/aspose.slides.export/swfoptions/logo_image_bytes) is opgegeven. |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/swfoptions/jpeg_quality/) | Specificeert de kwaliteit van JPEG-afbeeldingen.<br/>            Standaard is 95. |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/swfoptions/slides_layout_options/) | Geeft of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions).<br/>            Deze eigenschap ondersteunt niet het toewijzen van objecten van type [`HandoutLayoutingOptions`](/slides/python-net/nl/aspose.slides.export/handoutlayoutingoptions) |

### Zie ook
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* klasse [`SwfOptions`](/slides/python-net/nl/aspose.slides.export/swfoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)