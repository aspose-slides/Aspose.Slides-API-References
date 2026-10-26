---
title: PdfOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/pdfoptions/
---
## PdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

**Inheritance:**[`PdfOptions`](/slides/python-net/nl/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

Het PdfOptions-type stelt de volgende leden bloot:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/pdfoptions/__init__/#) | Default constructor. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/pdfoptions/warning_callback/) | Geeft of stelt een object in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken.<br/>            Lezen/Schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/pdfoptions/progress_callback/) | Stelt een callback-object voor om voortgangsupdates bij het opslaan in percentage te ontvangen.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/pdfoptions/default_regular_font/) | Geeft of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/pdfoptions/gradient_style/) | Geeft of stelt de visuele stijl van de gradient in.<br/>            Lezen/Schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/pdfoptions/skip_java_script_links/) | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie.<br/>            Lezen/Schrijven **bool**. De standaardwaarde is **false**. |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/pdfoptions/slides_layout_options/) | Geeft of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/pdfoptions/ink_options/) | Stelt opties beschikbaar die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/pdfoptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`text_compression`](/slides/python-net/nl/aspose.slides.export/pdfoptions/text_compression/) | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document.<br/>            Lezen/Schrijven [`PdfTextCompression`](/slides/python-net/nl/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/nl/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd.<br/>            Als ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document.<br/>            Het selecteren van de beste compressieverhouding voor afbeeldingen is computationeel intensief en vereist extra RAM, en deze optie is standaard **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/nl/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Bepaalt of Aspose.Slides algemene lettertypen voor ASCII-tekst (code-bereik 33..127) insluit.<br/>            Lettertypen voor tekens met codes groter dan 127 worden altijd ingesloten.<br/>            De lijst met algemene lettertypen omvat de basis-14 lettertypen van PDF en extra door de gebruiker opgegeven lettertypen.<br/>            Lezen/Schrijven **bool**. |
| [`additional_common_font_families`](/slides/python-net/nl/aspose.slides.export/pdfoptions/additional_common_font_families/) | Geeft of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies waarmee Aspose.Slides rekening moet houden als gemeenschappelijk.<br/>            Lezen/Schrijven **str**[]. |
| [`embed_full_fonts`](/slides/python-net/nl/aspose.slides.export/pdfoptions/embed_full_fonts/) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen de gebruikte subset.<br/>            Lezen/Schrijven **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/nl/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette opmaak ondersteunt.<br/>            Deze benadering kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren.<br/>            Lezen/Schrijven **bool**. |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/pdfoptions/jpeg_quality/) | Geeft of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt.<br/>            Lezen/Schrijven **int**. |
| [`compliance`](/slides/python-net/nl/aspose.slides.export/pdfoptions/compliance/) | Gewenst conformatieniveau voor het gegenereerde PDF-document.<br/>            Lezen/Schrijven [`PdfCompliance`](/slides/python-net/nl/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/nl/aspose.slides.export/pdfoptions/password/) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen.<br/>            Lezen/Schrijven **str**. |
| [`access_permissions`](/slides/python-net/nl/aspose.slides.export/pdfoptions/access_permissions/) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.<br/>            Zie [`PdfAccessPermissions`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/nl/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Waar om alle metabestanden die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen.<br/>            Lezen/Schrijven **bool**. |
| [`sufficient_resolution`](/slides/python-net/nl/aspose.slides.export/pdfoptions/sufficient_resolution/) | Geeft of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt.<br/>            <br/>De eigenschap beïnvloedt bestandsomvang, exporttijd en afbeeldingskwaliteit.<br/><br/><br/>De standaardwaarde is **96**.<br/><br/><br/>            Lezen/Schrijven **float**. |
| [`draw_slides_frame`](/slides/python-net/nl/aspose.slides.export/pdfoptions/draw_slides_frame/) | Waar om een zwart kader rond elke dia te tekenen.<br/>             Lezen/Schrijven **bool**. |
| [`image_transparent_color`](/slides/python-net/nl/aspose.slides.export/pdfoptions/image_transparent_color/) | Geeft of stelt de transparante kleur van de afbeelding in. |
| [`apply_image_transparent`](/slides/python-net/nl/aspose.slides.export/pdfoptions/apply_image_transparent/) | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [`include_ole_data`](/slides/python-net/nl/aspose.slides.export/pdfoptions/include_ole_data/) | Waar om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de resulterende PDF.<br/>            Lezen/Schrijven **bool**. |

### Zie ook
* klasse [`PdfOptions`](/slides/python-net/nl/aspose.slides.export/pdfoptions)
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)