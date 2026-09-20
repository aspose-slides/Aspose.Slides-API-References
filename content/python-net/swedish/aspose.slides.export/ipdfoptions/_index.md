---
title: IPdfOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ipdfoptions/
---
## IPdfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i Pdf format.

IPdfOptions-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/text_compression/) | Anger komprimeringstyp som ska användas för allt textinnehåll i dokumentet.<br/>            Läs/skriv [`PdfTextCompression`](/slides/python-net/sv/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indikerar om den mest effektiva komprimeringen (istället för standardalternativet) för varje bild måste väljas <br/>            automatiskt. Om den sätts till **bool**.true, kommer den mest lämpliga komprimeringsalgoritmen <br/>            att väljas för varje bild i presentationen, vilket leder till en mindre storlek på det resulterande PDF-dokumentet. <br/>            Val av bästa bildkomprimeringsförhållande är beräkningsmässigt dyrt och kräver <br/>            en extra mängd RAM, och detta alternativ är **bool**.false som standard. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Sant för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127.<br/>            Teckensnitt för teckenkoder över 127 bäddas alltid in.<br/>            Läs/skriv **bool**. |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standard är `false`. |
| [`additional_common_font_families`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Returnerar eller ställer in en array av användardefinierade namn på typsnittsfamiljer som Aspose.Slides bör betrakta som vanliga.<br/>            Läs/skriv **str**[]. |
| [`embed_full_fonts`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Bestämmer om alla tecken i teckensnittet ska bäddas in eller endast en använd delmängd.<br/>            Läs/skriv **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Anger om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil.<br/>            Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF-dokumentet för vissa teckensnitt.<br/>            Läs/skriv **bool**. |
| [`jpeg_quality`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/jpeg_quality/) | Returnerar eller ställer in ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet.<br/>            Läs/skriv **int**. |
| [`compliance`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/compliance/) | Önskad efterlevnadsnivå för det genererade PDF-dokumentet.<br/>            Läs/skriv [`PdfCompliance`](/slides/python-net/sv/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/password/) | Ställer in användarlösenord för att skydda PDF-dokumentet.<br/>            Läs/skriv **str**. |
| [`access_permissions`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/access_permissions/) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas<br/>            med användaråtkomst. Se [`PdfAccessPermissions`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder.<br/>            Läs/skriv **bool**. |
| [`sufficient_resolution`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Returnerar eller ställer in ett värde som bestämmer upplösningen på bilder i PDF-dokumentet.<br/>            <br/>Egenskapen påverkar filstorleken, exporttiden och bildkvaliteten.<br/><br/><br/>Standardvärdet är **96** .<br/><br/><br/>            Läs/skriv **float**. |
| [`draw_slides_frame`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Sant för att rita en svart ram runt varje bild.<br/>             Läs/skriv **bool**. |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/slides_layout_options/) | Hämtar eller ställer in läget där bilder placeras på sidan när en presentation exporteras [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/image_transparent_color/) | Hämtar eller ställer in bildens transparentfärg. |
| [`apply_image_transparent`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Applicerar den angivna transparentfärgen på en bild om `true`. |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i det exporterade dokumentet.<br/>            Läs-endast [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/include_ole_data/) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-filen.<br/>            Läs/skriv **bool**. |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)