---
title: ISVGOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/isvgoptions/
---
## ISVGOptions klass

Representerar ett SVG-alternativ.

ISVGOptions-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/sv/aspose.slides.export/isvgoptions/vectorize_text/) | Bestämmer om texten på en bild kommer att sparas som grafik.<br/>            Läs/skriv **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/sv/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Returnerar eller anger den lägre upplösningsgränsen för metafil-rasterisering.<br/>            Läs/skriv **int**. |
| [`disable_3d_text`](/slides/python-net/sv/aspose.slides.export/isvgoptions/disable_3d_text/) | Bestämmer om 3D-text är inaktiverad i SVG.<br/>            Läs/skriv **bool**. |
| [`disable_gradient_split`](/slides/python-net/sv/aspose.slides.export/isvgoptions/disable_gradient_split/) | Inaktiverar uppdelning av FromCornerX- och FromCenter-gradienter.<br/>            Läs/skriv **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/sv/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 saknar möjlighet att definiera insatser för markörer.<br/>            Aspose.Slides SVG-skrivmotor har en lösning för det problemet:<br/>            den beskär slutet av linjen med pil, så att linjen inte överlappar markörer.<br/>            Detta alternativ stänger av sådant beteende.<br/>            Läs/skriv **bool**. |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/isvgoptions/jpeg_quality/) | Bestämmer JPEG-kodningskvaliteten.<br/>            Läs/skriv **int**. |
| [`shape_formatting_controller`](/slides/python-net/sv/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Returnerar och anger ett återuppringnings-gränssnitt som låter användaren kontrollera formkonvertering.<br/>            Läs/skriv [`ISvgShapeFormattingController`](/slides/python-net/sv/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/sv/aspose.slides.export/isvgoptions/pictures_compression/) | Representerar bildkomprimeringsnivån<br/>            Läs/skriv [`ISVGOptions.pictures_compression`](/slides/python-net/sv/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/sv/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. Om sant tas de beskurna <br/>            delarna bort, om falskt kommer de att serialiseras i dokumentet (vilket möjligtvis kan leda till en <br/>            större fil)<br/>            Läs/skriv **bool**. |
| [`use_frame_size`](/slides/python-net/sv/aspose.slides.export/isvgoptions/use_frame_size/) | Bestämmer om textramen ska inkluderas i ett renderingsområde eller ej.<br/>            Läs/skriv **bool**.<br/>            Standardvärdet är falskt. |
| [`use_frame_rotation`](/slides/python-net/sv/aspose.slides.export/isvgoptions/use_frame_rotation/) | Bestämmer om den specificerade rotationen av formen ska utföras vid rendering eller ej.<br/>            Läs/skriv **bool**.<br/>            Standardvärdet är sant. |
| [`external_fonts_handling`](/slides/python-net/sv/aspose.slides.export/isvgoptions/external_fonts_handling/) | Bestämmer ett sätt att hantera externt inlästa typsnitt.<br/>            Läs/skriv [`SvgExternalFontsHandling`](/slides/python-net/sv/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/isvgoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterat dokument.<br/>            Läs-endast [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/sv/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer.<br/>            När den är satt till `true`, kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap satt till `false`. |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)