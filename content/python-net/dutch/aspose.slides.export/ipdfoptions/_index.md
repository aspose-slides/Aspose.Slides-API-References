---
title: IPdfOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

Het type IPdfOptions biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`text_compression`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/text_compression/) | Specificeert het compressietype dat wordt gebruikt voor alle tekstuele inhoud in het document.<br/>            Lezen/Schrijven [`PdfTextCompression`](/slides/python-net/nl/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd <br/>            automatisch. Als ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie de meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere omvang van het resulterende PDF-document. <br/>            Het selecteren van de beste compressieverhouding is rekenintensief en vereist <br/>            extra RAM, en deze optie is standaard **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127.<br/>            Lettertypen voor teken-codes groter dan 127 worden altijd ingesloten.<br/>            Lezen/Schrijven **bool**. |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`additional_common_font_families`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Retourneert of stelt een array in van door de gebruiker gedefinieerde namen van lettertype-families die Aspose.Slides als algemeen moet beschouwen.<br/>            Lezen/Schrijven **str**[]. |
| [`embed_full_fonts`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of slechts een gebruikte subset.<br/>            Lezen/Schrijven **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette stijl ondersteunt.<br/>            Deze aanpak kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren.<br/>            Lezen/Schrijven **bool**. |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/jpeg_quality/) | Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen binnen het PDF-document bepaalt.<br/>            Lezen/Schrijven **int**. |
| [`compliance`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/compliance/) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document.<br/>            Lezen/Schrijven [`PdfCompliance`](/slides/python-net/nl/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/password/) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen.<br/>            Lezen/Schrijven **str**. |
| [`access_permissions`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/access_permissions/) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend<br/>            met gebruikersrechten. Zie [`PdfAccessPermissions`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True om alle metabestanden die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen.<br/>            Lezen/Schrijven **bool**. |
| [`sufficient_resolution`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Retourneert of stelt een waarde in die de resolutie van afbeeldingen binnen het PDF-document bepaalt.<br/>            <br/>Eigenschap beïnvloedt de bestandsgrootte, exporttijd en beeldkwaliteit.<br/><br/><br/>De standaardwaarde is **96** .<br/><br/><br/>            Lezen/Schrijven **float**. |
| [`draw_slides_frame`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True om een zwart kader rond elke dia te tekenen.<br/>            Lezen/Schrijven **bool**. |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/slides_layout_options/) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/image_transparent_color/) | Haalt op of stelt de transparante kleur van de afbeelding in. |
| [`apply_image_transparent`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/include_ole_data/) | True om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de resulterende PDF.<br/>            Lezen/Schrijven **bool**. |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)