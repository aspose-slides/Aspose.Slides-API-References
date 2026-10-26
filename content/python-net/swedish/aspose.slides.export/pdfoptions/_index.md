---
title: PdfOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/pdfoptions/
---
## PdfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i Pdf-format.

**Arv:**[`PdfOptions`](/slides/python-net/sv/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

PdfOptions-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/pdfoptions/__init__/#) | Standardkonstruktor. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/pdfoptions/warning_callback/) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/pdfoptions/progress_callback/) | Representerar ett återuppringningsobjekt för sparande av förloppsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/pdfoptions/default_regular_font/) | Returnerar eller anger teckensnitt som används om källteckensnittet inte finns.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/pdfoptions/gradient_style/) | Returnerar eller anger den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/pdfoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. <br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/pdfoptions/slides_layout_options/) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/pdfoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument.<br/>            Endast läsning [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/pdfoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standard är `false`. |
| [`text_compression`](/slides/python-net/sv/aspose.slides.export/pdfoptions/text_compression/) | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet.<br/>            Läs/skriv [`PdfTextCompression`](/slides/python-net/sv/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/sv/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas <br/>            automatiskt. Om satt till **bool**.true, kommer den mest lämpliga kompressionsalgoritmen för varje bild i presentationen att väljas, vilket leder till en mindre storlek på det resulterande PDF-dokumentet. <br/>            Val av bästa bildkomprimeringsförhållande är beräkningsmässigt dyrt och kräver <br/>            en extra mängd RAM, och detta alternativ är **bool**.false som standard. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/sv/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Bestämmer om Aspose.Slides ska bädda in vanliga teckensnitt för ASCII (33..127 kodintervall) text.<br/>            Teckensnitt för teckenkoder över 127 är alltid inbäddade.<br/>            Listan med vanliga teckensnitt inkluderar PDF:s grundläggande 14 teckensnitt och ytterligare användarspecificerade teckensnitt.<br/>            Läs/skriv **bool**. |
| [`additional_common_font_families`](/slides/python-net/sv/aspose.slides.export/pdfoptions/additional_common_font_families/) | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som vanliga.<br/>            Läs/skriv **str**[]. |
| [`embed_full_fonts`](/slides/python-net/sv/aspose.slides.export/pdfoptions/embed_full_fonts/) | Bestämmer om alla tecken i teckensnittet ska bäddas in eller endast den använda delmängden.<br/>            Läs/skriv **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/sv/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil.<br/>            Denna metod kan förbättra kvaliteten på text i den resulterande PDF:en för vissa teckensnitt.<br/>            Läs/skriv **bool**. |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/pdfoptions/jpeg_quality/) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet.<br/>            Läs/skriv **int**. |
| [`compliance`](/slides/python-net/sv/aspose.slides.export/pdfoptions/compliance/) | Önskad efterlevnadsnivå för det genererade PDF-dokumentet.<br/>            Läs/skriv [`PdfCompliance`](/slides/python-net/sv/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/sv/aspose.slides.export/pdfoptions/password/) | Anger användarlösenord för att skydda PDF-dokumentet. <br/>            Läs/skriv **str**. |
| [`access_permissions`](/slides/python-net/sv/aspose.slides.export/pdfoptions/access_permissions/) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas<br/>            med användaråtkomst. Se [`PdfAccessPermissions`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/sv/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder.<br/>            Läs/skriv **bool**. |
| [`sufficient_resolution`](/slides/python-net/sv/aspose.slides.export/pdfoptions/sufficient_resolution/) | Returnerar eller anger ett värde som bestämmer upplösningen på bilder i PDF-dokumentet.<br/>            <br/>Egenskapen påverkar filstorlek, exporttid och bildkvalitet.<br/><br/><br/>Standardvärdet är **96** .<br/><br/><br/>            Läs/skriv **float**. |
| [`draw_slides_frame`](/slides/python-net/sv/aspose.slides.export/pdfoptions/draw_slides_frame/) | Sant för att rita en svart ram runt varje bild.<br/>             Läs/skriv **bool**. |
| [`image_transparent_color`](/slides/python-net/sv/aspose.slides.export/pdfoptions/image_transparent_color/) | Hämtar eller anger bildens transparenta färg. |
| [`apply_image_transparent`](/slides/python-net/sv/aspose.slides.export/pdfoptions/apply_image_transparent/) | Tillämpar den angivna transparenta färgen på en bild om `true`. |
| [`include_ole_data`](/slides/python-net/sv/aspose.slides.export/pdfoptions/include_ole_data/) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF:en.<br/>            Läs/skriv **bool**. |


### Se även
* klass [`PdfOptions`](/slides/python-net/sv/aspose.slides.export/pdfoptions)
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)