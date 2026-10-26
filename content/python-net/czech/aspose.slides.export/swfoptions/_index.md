---
title: SwfOptions class
second_title: Aspose.Slides pro Python přes .NET API referenční příručka
description: 
type: docs
url: /cs/aspose.slides.export/swfoptions/
---
## SwfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.

**Inheritance:**[`SwfOptions`](/slides/python-net/cs/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ SwfOptions zveřejňuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/swfoptions/__init__/#) | Výchozí konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/swfoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen.<br/>            Číst/zapsat [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/swfoptions/progress_callback/) | Representuje objekt zpětného volání pro ukládání průběhu v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/swfoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že výchozí písmo není nalezeno.<br/>            Číst/zapsat **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/swfoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Číst/zapsat [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/swfoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. <br/>            Číst/zapsat **bool**. Výchozí hodnota je **false**. |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_hidden_slides/) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`compressed`](/slides/python-net/cs/aspose.slides.export/swfoptions/compressed/) | Určuje, zda má být vygenerovaný SWF dokument komprimován nebo ne.<br/>            Výchozí hodnota je `true`. |
| [`viewer_included`](/slides/python-net/cs/aspose.slides.export/swfoptions/viewer_included/) | Určuje, zda má vygenerovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů nebo ne.<br/>            Výchozí hodnota je `true`. |
| [`show_page_border`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_page_border/) | Určuje, zda má být okraj kolem stránek zobrazen. Výchozí hodnota je true. |
| [`show_full_screen`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_full_screen/) | Zobrazit/skryt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`show_page_stepper`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_page_stepper/) | Zobrazit/skryt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`show_search`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_search/) | Zobrazit/skryt sekci hledání. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`show_top_pane`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_top_pane/) | Zobrazit/skryt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`show_bottom_pane`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_bottom_pane/) | Zobrazit/skryt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`show_left_pane`](/slides/python-net/cs/aspose.slides.export/swfoptions/show_left_pane/) | Zobrazit/skryt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [`start_open_left_pane`](/slides/python-net/cs/aspose.slides.export/swfoptions/start_open_left_pane/) | Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false. |
| [`enable_context_menu`](/slides/python-net/cs/aspose.slides.export/swfoptions/enable_context_menu/) | Povolit/zakázat kontextové menu. Výchozí hodnota je true. |
| [`logo_image_bytes`](/slides/python-net/cs/aspose.slides.export/swfoptions/logo_image_bytes/) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče.<br/>            Obrázek by měl být PNG o rozměrech 32 × 64 pixelů, jinak může být logo zobrazeno nesprávně. |
| [`logo_link`](/slides/python-net/cs/aspose.slides.export/swfoptions/logo_link/) | Vrací nebo nastavuje úplnou adresu hypertextového odkazu pro logo.<br/>            Má efekt pouze pokud je zadán [`SwfOptions.logo_image_bytes`](/slides/python-net/cs/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/swfoptions/jpeg_quality/) | Určuje kvalitu JPEG obrázků.<br/>            Výchozí hodnota je 95. |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/swfoptions/slides_layout_options/) | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). <br/>            Tato vlastnost nepodporuje přiřazování objektů typu [`HandoutLayoutingOptions`](/slides/python-net/cs/aspose.slides.export/handoutlayoutingoptions) |

### Viz také
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* třída [`SwfOptions`](/slides/python-net/cs/aspose.slides.export/swfoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)