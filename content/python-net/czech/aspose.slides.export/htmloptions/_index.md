---
title: HtmlOptions class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides.export/htmloptions/
---
## HtmlOptions třída

Representuje možnosti exportu HTML.

**Dědičnost:**[`HtmlOptions`](/slides/python-net/cs/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ HtmlOptions vystavuje následující členy:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/cs/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Vytvoří nový objekt HtmlOptions specifikující zpětné volání. |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/htmloptions/__init__/#) | Vytvoří nový objekt HtmlOptions pro uložení do jediného souboru HTML. |

## Vlastnosti

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/htmloptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen.<br/>            Read/write [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/htmloptions/progress_callback/) | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/htmloptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo nebylo nalezeno.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/htmloptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Read/write [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/htmloptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Read/write **bool**. Výchozí hodnota je **false**. |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/htmloptions/slides_layout_options/) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/htmloptions/ink_options/) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.<br/>            Read-only [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/htmloptions/show_hidden_slides/) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`html_formatter`](/slides/python-net/cs/aspose.slides.export/htmloptions/html_formatter/) | Vrací nebo nastavuje HTML šablonu.<br/>            Read/write [`IHtmlFormatter`](/slides/python-net/cs/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/cs/aspose.slides.export/htmloptions/disable_font_ligatures/) | Získá nebo nastaví hodnotu, která určuje, zda je text vykreslován bez použití ligatur.<br/>            Když je nastavena na `true`, ligatury budou ve výstupu zakázány. Ve výchozím stavu je tato vlastnost nastavena na `false`. |
| [`slide_image_format`](/slides/python-net/cs/aspose.slides.export/htmloptions/slide_image_format/) | Vrací nebo nastavuje možnosti formátu obrázku snímku.<br/>            Read/write [`ISlideImageFormat`](/slides/python-net/cs/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/htmloptions/jpeg_quality/) | Vrací nebo nastaví hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu.<br/>            Read/write **int**. |
| [`pictures_compression`](/slides/python-net/cs/aspose.slides.export/htmloptions/pictures_compression/) | Reprezentuje úroveň komprese obrázků |
| [`delete_pictures_cropped_areas`](/slides/python-net/cs/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Boolean příznak označuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté <br/>            části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k <br/>            většímu souboru) |
| [`svg_responsive_layout`](/slides/python-net/cs/aspose.slides.export/htmloptions/svg_responsive_layout/) | True pro vyloučení atributů šířky a výšky z svg kontejneru – to způsobí responzivní rozvržení. False – v opačném případě.<br/>            Read/write **bool**. |


### Viz také
* třída [`HtmlOptions`](/slides/python-net/cs/aspose.slides.export/htmloptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)