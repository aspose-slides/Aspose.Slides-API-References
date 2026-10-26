---
title: LayoutSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/layoutslide/
---
## LayoutSlide klasse

Representeert een lay-outdia.

**Inheritance:**[`LayoutSlide`](/slides/python-net/nl/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)

Het LayoutSlide type biedt de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/layoutslide/shapes/) | Retourneert de vormen van een dia.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/layoutslide/controls/) | Retourneert de verzameling ActiveX-besturingselementen op een dia.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/layoutslide/name/) | Retourneert of stelt de naam van een dia in.<br/>            Lezen/Schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/layoutslide/slide_id/) | Retourneert de ID van een dia.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/layoutslide/custom_data/) | Retourneert de aangepaste gegevens van de dia.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/layoutslide/timeline/) | Retourneert het animatietijdlijnobject.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/layoutslide/slide_show_transition/) | Retourneert het Transition-object dat informatie bevat over<br/>            hoe de opgegeven dia vordert tijdens een diavoorstelling.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/layoutslide/background/) | Retourneert de achtergrond van de dia.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/layoutslide/hyperlink_queries/) | Biedt gemakkelijke toegang tot ingesloten hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/layoutslide/show_master_shapes/) | Specificeert of vormen op de masterdia getoond moeten worden op dia's of niet.<br/>            Lezen/Schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/layoutslide/presentation/) | Retourneert de IPresentation-interface.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/layoutslide/header_footer_manager/) | Retourneert de HeaderFooter-beheerder van de lay-outdia.<br/>            Alleen-lezen [`ILayoutSlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/nl/aspose.slides/layoutslide/placeholder_manager/) | Retourneert de placeholder-beheerder van de lay-outdia.<br/>            Alleen-lezen [`ILayoutPlaceholderManager`](/slides/python-net/nl/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/nl/aspose.slides/layoutslide/master_slide/) | Retourneert of stelt de masterdia voor een lay-out in.<br/>            Lezen/Schrijven [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/layoutslide/theme_manager/) | Retourneert de overschrijvende themabeheerder.<br/>            Alleen-lezen [`IOverrideThemeManager`](/slides/python-net/nl/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/nl/aspose.slides/layoutslide/layout_type/) | Retourneert het lay-outtype van deze lay-outdia.<br/>            Alleen-lezen [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/nl/aspose.slides/layoutslide/has_depending_slides/) | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze lay-outdia.<br/>            Alleen-lezen **bool**. |
| [`drawing_guides`](/slides/python-net/nl/aspose.slides/layoutslide/drawing_guides/) | Retourneert een verzameling tekengidsen voor de lay-outdia.<br/>            Alleen-lezen [`IDrawingGuidesCollection`](/slides/python-net/nl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/nl/aspose.slides/layoutslide/slide/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle accepteerbare vormen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle accepteerbare vormen. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/layoutslide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            Retourwaarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, zoals SlideId, en dynamische inhoud, zoals de huidige datumwaarde in een Date-placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/layoutslide/create_theme_effective/#) | Retourneert een effectief thema voor deze dia. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Vindt de eerste verschijning van een vorm met de opgegeven alternatieve tekst. |
| [`remove(self)`](/slides/python-net/nl/aspose.slides/layoutslide/remove/#) | Verwijdert de lay-out uit de presentatie. |
| [`get_depending_slides(self)`](/slides/python-net/nl/aspose.slides/layoutslide/get_depending_slides/#) | Retourneert een array met alle dia's die afhankelijk zijn van deze lay-outdia. |

### Zie ook
* klasse [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)
* klasse [`LayoutSlide`](/slides/python-net/nl/aspose.slides/layoutslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)