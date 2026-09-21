---
title: Slide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slide/
---
## Slide klasse

Representeert een dia in een presentatie.

**Erfenis:**[`Slide`](/slides/python-net/nl/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)

Het Slide-type bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/slide/shapes/) | Retourneert de vormen van een dia.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/slide/controls/) | Retourneert de collectie van ActiveX-besturingselementen op een dia.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/slide/name/) | Retourneert of stelt de naam van een dia in.<br/>            Lezen/Schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/slide/slide_id/) | Retourneert de ID van een dia.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/slide/custom_data/) | Retourneert de aangepaste gegevens van de dia.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/slide/timeline/) | Retourneert het animatietijdlijnobject.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/slide/slide_show_transition/) | Retourneert het Transition-object dat informatie bevat over<br/>            hoe de opgegeven dia vordert tijdens een diavoorstelling.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/slide/background/) | Retourneert de achtergrond van de dia.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/slide/hyperlink_queries/) | Biedt gemakkelijke toegang tot opgenomen hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/slide/show_master_shapes/) | Specificeert of vormen op de masterdia al dan niet op dia's moeten worden weergegeven.<br/>            Lezen/Schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/slide/presentation/) | Retourneert de IPresentation-interface.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/slide/header_footer_manager/) | Retourneert de HeaderFooter-beheerder van de dia.<br/>            Alleen-lezen [`ISlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/slide/theme_manager/) | Retourneert de overschrijfende thema-beheerder.<br/>            Alleen-lezen [`IOverrideThemeManager`](/slides/python-net/nl/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/nl/aspose.slides/slide/slide_number/) | Retourneert een nummer van de dia.<br/>            De index van de dia in de [`Presentation.slides`](/slides/python-net/nl/aspose.slides/presentation/slides)-collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber.<br/>            Lezen/Schrijven **int**. |
| [`hidden`](/slides/python-net/nl/aspose.slides/slide/hidden/) | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling.<br/>            Lezen/Schrijven **bool**. |
| [`layout_slide`](/slides/python-net/nl/aspose.slides/slide/layout_slide/) | Retourneert of stelt de lay-outdia voor de huidige dia in.<br/>            Lezen/Schrijven [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/nl/aspose.slides/slide/notes_slide_manager/) | Staat toe om de notitiesdia te benaderen, toe te voegen en te verwijderen.<br/>            Alleen-lezen [`INotesSlideManager`](/slides/python-net/nl/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/nl/aspose.slides/slide/slide/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/slide/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele vormen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele vormen. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/slide/get_image/#float-float) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/slide/get_image/#) | Retourneert een Thumbnail Image-object (20% van de werkelijke grootte). |
| [`get_image(self, image_size)`](/slides/python-net/nl/aspose.slides/slide/get_image/#asposepydrawingsize) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [`get_image(self, options)`](/slides/python-net/nl/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Retourneert een Thumbnail tiff-afbeeldingsobject met opgegeven parameters. |
| [`get_image(self, options)`](/slides/python-net/nl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Retourneert een Thumbnail Image-object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [`get_image(self, options, image_size)`](/slides/python-net/nl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/slide/write_as_svg/#iorawiobase) | Slaat de dia-inhoud op als een SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de dia-inhoud op als een SVG-bestand. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/slide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            De teruggegeven waarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in de Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/slide/create_theme_effective/#) | Retourneert een effectief thema voor deze dia. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/slide/find_shape_by_alt_text/#str) | Vindt de eerste voorkoming van een vorm met de opgegeven alternatieve tekst. |
| [`write_as_emf(self, stream)`](/slides/python-net/nl/aspose.slides/slide/write_as_emf/#iorawiobase) | Slaat de dia-inhoud op als een EMF-bestand. |
| [`remove(self)`](/slides/python-net/nl/aspose.slides/slide/remove/#) | Verwijdert de dia uit de presentatie. |
| [`reset(self)`](/slides/python-net/nl/aspose.slides/slide/reset/#) | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/nl/aspose.slides/slide/get_slide_comments/#icommentauthor) | Retourneert alle dia-opmerkingen toegevoegd door een specifieke auteur. |

### Zie ook
* klasse [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)
* klasse [`Slide`](/slides/python-net/nl/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)