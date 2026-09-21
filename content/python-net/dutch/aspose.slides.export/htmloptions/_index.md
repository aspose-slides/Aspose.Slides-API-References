---
title: HtmlOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/htmloptions/
---
## HtmlOptions klasse

Stelt een HTML-exportoptie voor.

**Erfenis:**[`HtmlOptions`](/slides/python-net/nl/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

Het HtmlOptions-type geeft de volgende leden weer:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/nl/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Maakt een nieuw HtmlOptions-object dat een callback specificeert. |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/htmloptions/__init__/#) | Maakt een nieuw HtmlOptions-object voor het opslaan in een enkel HTML-bestand. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/htmloptions/warning_callback/) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken.<br/>            Lezen/Schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/htmloptions/progress_callback/) | Stelt een callback-object voor voor het opslaan van voortgangsupdates in procenten.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/htmloptions/default_regular_font/) | Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/htmloptions/gradient_style/) | Geeft de visuele stijl van de gradient terug of stelt deze in.<br/>            Lezen/Schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/htmloptions/skip_java_script_links/) | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie.<br/>            Lezen/Schrijven **bool**. De standaardwaarde is **false**. |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/htmloptions/slides_layout_options/) | Haal de modus op of stel deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/htmloptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/htmloptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`html_formatter`](/slides/python-net/nl/aspose.slides.export/htmloptions/html_formatter/) | Geeft de HTML-sjabloon terug of stelt deze in.<br/>            Lezen/Schrijven [`IHtmlFormatter`](/slides/python-net/nl/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/nl/aspose.slides.export/htmloptions/disable_font_ligatures/) | Haal een waarde op of stel een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen.<br/>            Wanneer ingesteld op `true`, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op `false`. |
| [`slide_image_format`](/slides/python-net/nl/aspose.slides.export/htmloptions/slide_image_format/) | Geeft de opties voor het dia-afbeeldingsformaat terug of stelt deze in.<br/>            Lezen/Schrijven [`ISlideImageFormat`](/slides/python-net/nl/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/nl/aspose.slides.export/htmloptions/jpeg_quality/) | Geeft een waarde terug of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in een PDF-document bepaalt.<br/>            Lezen/Schrijven **int**. |
| [`pictures_compression`](/slides/python-net/nl/aspose.slides.export/htmloptions/pictures_compression/) | Stelt het compressieniveau van de afbeeldingen voor |
| [`delete_pictures_cropped_areas`](/slides/python-net/nl/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Een booleaanse vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Als true worden de bijgesneden <br/>            delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk kan leiden tot een <br/>            groter bestand) |
| [`svg_responsive_layout`](/slides/python-net/nl/aspose.slides.export/htmloptions/svg_responsive_layout/) | True om breedte- en hoogte-attributen uit de svg-container uit te sluiten – dit maakt de lay-out responsief. False – anders.<br/>            Lezen/Schrijven **bool**. |

### Zie ook
* klasse [`HtmlOptions`](/slides/python-net/nl/aspose.slides.export/htmloptions)
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)