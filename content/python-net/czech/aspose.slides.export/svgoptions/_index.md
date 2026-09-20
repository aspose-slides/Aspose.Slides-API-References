---
title: SVGOptions class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/svgoptions/
---
## SVGOptions třída

Reprezentuje možnosti SVG.

**Dědičnost:**[`SVGOptions`](/slides/python-net/cs/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ SVGOptions vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/svgoptions/__init__/#) | Inicializuje novou instanci třídy SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/cs/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Inicializuje novou instanci třídy SVGOptions s určeným objektem řídícího vložení odkazu. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/svgoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda načítací proces bude pokračovat nebo bude přerušen.<br/>            Čtení/Zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/svgoptions/progress_callback/) | Reprezentuje objekt zpětného volání pro ukládání průběžných aktualizací v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/svgoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo nebylo nalezeno.<br/>            Čtení/Zápis **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/svgoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl přechodu.<br/>            Čtení/Zápis [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/svgoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Čtení/Zápis **bool**. Výchozí hodnota je **false**. |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/svgoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu.<br/>            Pouze pro čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/cs/aspose.slides.export/svgoptions/use_frame_size/) | Určuje, zda bude textový rámec zahrnut v oblasti vykreslování nebo ne.<br/>            Čtení/Zápis **bool**.<br/>            Výchozí hodnota je false. |
| [`use_frame_rotation`](/slides/python-net/cs/aspose.slides.export/svgoptions/use_frame_rotation/) | Určuje, zda provést určenou rotaci tvaru při vykreslování nebo ne.<br/>            Čtení/Zápis **bool**.<br/>            Výchozí hodnota je true. |
| [`vectorize_text`](/slides/python-net/cs/aspose.slides.export/svgoptions/vectorize_text/) | Určuje, zda bude text na snímku uložen jako grafika.<br/>            Čtení/Zápis **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/cs/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Vrací nebo nastavuje spodní limit rozlišení pro rasterizaci metafile.<br/>            Čtení/Zápis **int**. |
| [`disable_3d_text`](/slides/python-net/cs/aspose.slides.export/svgoptions/disable_3d_text/) | Určuje, zda je 3D text v SVG zakázán.<br/>            Čtení/Zápis **bool**. |
| [`disable_gradient_split`](/slides/python-net/cs/aspose.slides.export/svgoptions/disable_gradient_split/) | Zakazuje rozdělení přechodů FromCornerX a FromCenter.<br/>            Čtení/Zápis **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/cs/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 postrádá schopnost definovat odsazení pro značky.<br/>            Aspose.Slides SVG zápisový engine má pro tento problém obcházení:<br/>            ořízne koncový řádek s šipkou, takže řádek nepřekrývá značky.<br/>            Tato volba vypíná takové chování.<br/>            Čtení/Zápis **bool**. |
| [`default`](/slides/python-net/cs/aspose.slides.export/svgoptions/default/) | Vrací výchozí nastavení.<br/>            Pouze pro čtení [`SVGOptions`](/slides/python-net/cs/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/cs/aspose.slides.export/svgoptions/simple/) | Vrací nastavení pro nejjednodušší a nejmenší generování SVG souboru.<br/>            Pouze pro čtení [`SVGOptions`](/slides/python-net/cs/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/cs/aspose.slides.export/svgoptions/wysiwyg/) | Vrací nastavení pro nejpřesnější generování SVG souboru.<br/>            Pouze pro čtení [`SVGOptions`](/slides/python-net/cs/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/svgoptions/jpeg_quality/) | Určuje kvalitu kódování JPEG.<br/>            Čtení/Zápis **int**. |
| [`shape_formatting_controller`](/slides/python-net/cs/aspose.slides.export/svgoptions/shape_formatting_controller/) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru.<br/>            Čtení/Zápis [`ISvgShapeFormattingController`](/slides/python-net/cs/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/cs/aspose.slides.export/svgoptions/pictures_compression/) | Reprezentuje úroveň komprese obrázků |
| [`delete_pictures_cropped_areas`](/slides/python-net/cs/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Boolovská vlajka ukazuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté <br/>            části budou odstraněny, pokud je false, budou serializovány v dokumentu (což může případně vést k <br/>            většímu souboru) |
| [`external_fonts_handling`](/slides/python-net/cs/aspose.slides.export/svgoptions/external_fonts_handling/) | Určuje způsob zacházení s externě načtenými písmy.<br/>            Čtení/Zápis [`SvgExternalFontsHandling`](/slides/python-net/cs/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/cs/aspose.slides.export/svgoptions/disable_font_ligatures/) | Vrací nebo nastavuje hodnotu určující, zda je text vykreslen bez použití ligatur.<br/>            Když je nastaveno na `true`, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na `false`. |

### Viz také
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* třída [`SVGOptions`](/slides/python-net/cs/aspose.slides.export/svgoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)