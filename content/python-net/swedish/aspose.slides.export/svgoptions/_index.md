---
title: SVGOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/svgoptions/
---
## SVGOptions klass

Representerar ett SVG-alternativ.

**Arv:**[`SVGOptions`](/slides/python-net/sv/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

SVGOptions-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/svgoptions/__init__/#) | Initierar en ny instans av SVGOptions-klassen. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/sv/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initierar en ny instans av SVGOptions-klassen med angivet länk-inbäddnings-kontrollerobjekt. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/svgoptions/warning_callback/) | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/svgoptions/progress_callback/) | Representerar ett återuppringningsobjekt för att spara förloppsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/svgoptions/default_regular_font/) | Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/svgoptions/gradient_style/) | Returnerar eller sätter den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/svgoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas.<br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/svgoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument.<br/>            Endast läsning [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/sv/aspose.slides.export/svgoptions/use_frame_size/) | Avgör om textramen ska inkluderas i ett renderingsområde eller inte.<br/>            Läs/skriv **bool**.<br/>            Standardvärdet är false. |
| [`use_frame_rotation`](/slides/python-net/sv/aspose.slides.export/svgoptions/use_frame_rotation/) | Avgör om den angivna rotationen av formen ska utföras vid rendering eller inte.<br/>            Läs/skriv **bool**.<br/>            Standardvärdet är true. |
| [`vectorize_text`](/slides/python-net/sv/aspose.slides.export/svgoptions/vectorize_text/) | Avgör om texten på en bildruta ska sparas som grafik.<br/>            Läs/skriv **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/sv/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Returnerar eller sätter den lägre upplösningsgränsen för metafils rasterisering.<br/>            Läs/skriv **int**. |
| [`disable_3d_text`](/slides/python-net/sv/aspose.slides.export/svgoptions/disable_3d_text/) | Avgör om 3D-text är inaktiverad i SVG.<br/>            Läs/skriv **bool**. |
| [`disable_gradient_split`](/slides/python-net/sv/aspose.slides.export/svgoptions/disable_gradient_split/) | Inaktiverar delning av FromCornerX- och FromCenter-gradienter.<br/>            Läs/skriv **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/sv/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 saknar möjlighet att definiera insättningar för markörer.<br/>            Aspose.Slides SVG-skrivningsmotor har en lösning för detta problem:<br/>            den beskär slutet av linjen med pil, så att linjen inte överlappar markörer.<br/>            Detta alternativ stänger av sådant beteende.<br/>            Läs/skriv **bool**. |
| [`default`](/slides/python-net/sv/aspose.slides.export/svgoptions/default/) | Returnerar standardinställningarna.<br/>            Endast läsning [`SVGOptions`](/slides/python-net/sv/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/sv/aspose.slides.export/svgoptions/simple/) | Returnerar inställningar för den enklaste och minsta SVG-filgenereringen.<br/>            Endast läsning [`SVGOptions`](/slides/python-net/sv/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/sv/aspose.slides.export/svgoptions/wysiwyg/) | Returnerar inställningar för den mest exakta SVG-filgenereringen.<br/>            Endast läsning [`SVGOptions`](/slides/python-net/sv/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/svgoptions/jpeg_quality/) | Avgör JPEG-kodningskvaliteten.<br/>            Läs/skriv **int**. |
| [`shape_formatting_controller`](/slides/python-net/sv/aspose.slides.export/svgoptions/shape_formatting_controller/) | Returnerar och sätter ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering.<br/>            Läs/skriv [`ISvgShapeFormattingController`](/slides/python-net/sv/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/sv/aspose.slides.export/svgoptions/pictures_compression/) | Representerar komprimeringsnivån för bilder |
| [`delete_pictures_cropped_areas`](/slides/python-net/sv/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | En boolesk flagga som indikerar om de beskurna delarna förblir som en del av dokumentet. Om true tas de beskurna <br/>            delarna bort, om false kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en <br/>            större fil) |
| [`external_fonts_handling`](/slides/python-net/sv/aspose.slides.export/svgoptions/external_fonts_handling/) | Avgör ett sätt att hantera externt laddade teckensnitt.<br/>            Läs/skriv [`SvgExternalFontsHandling`](/slides/python-net/sv/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/sv/aspose.slides.export/svgoptions/disable_font_ligatures/) | Hämtar eller sätter ett värde som indikerar om text renderas utan att använda ligaturer.<br/>            När satt till `true` kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är detta värde satt till `false`. |


### Se även
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* klass [`SVGOptions`](/slides/python-net/sv/aspose.slides.export/svgoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)