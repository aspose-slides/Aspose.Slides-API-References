---
title: ISVGOptions class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/isvgoptions/
---
## ISVGOptions třída

Představuje možnosti SVG.

Typ ISVGOptions vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/cs/aspose.slides.export/isvgoptions/vectorize_text/) | Určuje, zda bude text na snímku uložen jako grafika.<br/>            Číst/Zapisovat **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/cs/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Vrací nebo nastavuje limit nízkého rozlišení pro rasterizaci metafile.<br/>            Číst/Zapisovat **int**. |
| [`disable_3d_text`](/slides/python-net/cs/aspose.slides.export/isvgoptions/disable_3d_text/) | Určuje, zda je 3D text v SVG zakázán.<br/>            Číst/Zapisovat **bool**. |
| [`disable_gradient_split`](/slides/python-net/cs/aspose.slides.export/isvgoptions/disable_gradient_split/) | Zakazuje rozdělení gradientů FromCornerX a FromCenter.<br/>            Číst/Zapisovat **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/cs/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 postrádá schopnost definovat odsazení pro značky.<br/>            Aspose.Slides SVG engine pro zápis má řešení tohoto problému:<br/>            ořízne konec čáry s šipkou, takže čára nepřekrývá značky.<br/>            Toto nastavení vypíná takové chování.<br/>            Číst/Zapisovat **bool**. |
| [`jpeg_quality`](/slides/python-net/cs/aspose.slides.export/isvgoptions/jpeg_quality/) | Určuje kvalitu kódování JPEG.<br/>            Číst/Zapisovat **int**. |
| [`shape_formatting_controller`](/slides/python-net/cs/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů.<br/>            Číst/Zapisovat [`ISvgShapeFormattingController`](/slides/python-net/cs/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/cs/aspose.slides.export/isvgoptions/pictures_compression/) | Představuje úroveň komprese obrázků<br/>            Číst/Zapisovat [`ISVGOptions.pictures_compression`](/slides/python-net/cs/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/cs/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Logický příznak určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté <br/>            části budou odstraněny, pokud je false, budou serializovány v dokumentu (což může vést k <br/>            většímu souboru)<br/>            Číst/Zapisovat **bool**. |
| [`use_frame_size`](/slides/python-net/cs/aspose.slides.export/isvgoptions/use_frame_size/) | Určuje, zda bude rámeček textu zahrnut v oblasti vykreslování či nikoli.<br/>            Číst/Zapisovat **bool**.<br/>            Výchozí hodnota je false. |
| [`use_frame_rotation`](/slides/python-net/cs/aspose.slides.export/isvgoptions/use_frame_rotation/) | Určuje, zda provést specifikovanou rotaci tvaru při vykreslování či nikoli.<br/>            Číst/Zapisovat **bool**.<br/>            Výchozí hodnota je true. |
| [`external_fonts_handling`](/slides/python-net/cs/aspose.slides.export/isvgoptions/external_fonts_handling/) | Určuje způsob zacházení s externě načtenými fonty.<br/>            Číst/Zapisovat [`SvgExternalFontsHandling`](/slides/python-net/cs/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/isvgoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu.<br/>            Pouze ke čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/cs/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Získává nebo nastavuje hodnotu určující, zda je text vykreslen bez použití ligatur.<br/>            Když je nastavena na `true`, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na `false`. |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)