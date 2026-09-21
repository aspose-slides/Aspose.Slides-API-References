---
title: ISVGOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/isvgoptions/
---
## ISVGOptions klasse

Stelt een SVG-optie voor.

Het type ISVGOptions exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`vectorize_text`](/slides/python-net/nl/aspose.slides.export/isvgoptions/vectorize_text/) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische weergave.<br/>            Lezen/Schrijven **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/nl/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Geeft de ondergrens van de resolutie voor metafile rasterisatie terug of stelt deze in.<br/>            Lezen/Schrijven **int**. |
| [`disable_3d_text`](/slides/python-net/nl/aspose.slides.export/isvgoptions/disable_3d_text/) | Bepaalt of de 3D-tekst is uitgeschakeld in SVG.<br/>            Lezen/Schrijven **bool**. |
| [`disable_gradient_split`](/slides/python-net/nl/aspose.slides.export/isvgoptions/disable_gradient_split/) | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit.<br/>            Lezen/Schrijven **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/nl/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 heeft niet de mogelijkheid om insprongen voor markers te definiëren.<br/>            De SVG-schrijfmotor van Aspose.Slides heeft een oplossing voor dat probleem:<br/>            hij bijsnijdt het einde van de lijn met een pijl, zodat de lijn de markers niet overlapt.<br/>            Deze optie schakelt dat gedrag uit.<br/>            Lezen/Schrijven **bool**. |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/isvgoptions/jpeg_quality/) | Bepaalt de kwaliteit van JPEG-codering.<br/>            Lezen/Schrijven **int**. |
| [`shape_formatting_controller`](/slides/python-net/nl/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Geeft een callback-interface terug en stelt deze in die de gebruiker in staat om vormconversie te beheersen.<br/>            Lezen/Schrijven [`ISvgShapeFormattingController`](/slides/python-net/nl/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/nl/aspose.slides.export/isvgoptions/pictures_compression/) | Stelt het compressieniveau van afbeeldingen voor<br/>            Lezen/Schrijven [`ISVGOptions.pictures_compression`](/slides/python-net/nl/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/nl/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Een booleaanse vlag geeft aan of de bijgesneden delen deel van het document blijven. Indien true worden de bijgesneden <br/>            delen verwijderd, indien false worden ze geserialiseerd in het document (wat mogelijk kan leiden tot een <br/>            groter bestand)<br/>            Lezen/Schrijven **bool**. |
| [`use_frame_size`](/slides/python-net/nl/aspose.slides.export/isvgoptions/use_frame_size/) | Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied.<br/>            Lezen/Schrijven **bool**.<br/>            Standaardwaarde is false. |
| [`use_frame_rotation`](/slides/python-net/nl/aspose.slides.export/isvgoptions/use_frame_rotation/) | Bepaalt of de opgegeven rotatie van de vorm wordt toegepast tijdens het renderen of niet.<br/>            Lezen/Schrijven **bool**.<br/>            Standaardwaarde is true. |
| [`external_fonts_handling`](/slides/python-net/nl/aspose.slides.export/isvgoptions/external_fonts_handling/) | Bepaalt een manier om extern geladen lettertypen af te handelen.<br/>            Lezen/Schrijven [`SvgExternalFontsHandling`](/slides/python-net/nl/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/isvgoptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/nl/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Krijgt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken.<br/>            Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op `false`. |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)