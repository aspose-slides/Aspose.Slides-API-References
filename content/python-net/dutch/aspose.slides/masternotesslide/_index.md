---
title: MasterNotesSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masternotesslide/
---
## MasterNotesSlide klasse

Vertegenwoordigt de masterdia voor notities.

**Erfenis:**[`MasterNotesSlide`](/slides/python-net/nl/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)

Het MasterNotesSlide-type stelt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/masternotesslide/shapes/) | Retourneert de vormen van een dia.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/masternotesslide/controls/) | Retourneert de collectie van ActiveX-besturingselementen op een dia.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/masternotesslide/name/) | Retourneert of stelt de naam van een dia in.<br/>            Lezen/Schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/masternotesslide/slide_id/) | Retourneert de ID van een dia.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/masternotesslide/custom_data/) | Retourneert de aangepaste gegevens van de dia.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/masternotesslide/timeline/) | Retourneert animatie-tijdlijnobject.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/masternotesslide/slide_show_transition/) | Retourneert het Transition-object dat informatie bevat over<br/>            hoe de opgegeven dia vordert tijdens een diavoorstelling.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/masternotesslide/background/) | Retourneert de achtergrond van de dia.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/masternotesslide/hyperlink_queries/) | Biedt gemakkelijke toegang tot ingesloten hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/masternotesslide/show_master_shapes/) | Specificeert of vormen op de masterslide moeten worden weergegeven op dia's of niet.<br/>            Voor de masterslide zelf retourneert deze eigenschap altijd `false`.<br/>            Lezen/Schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/masternotesslide/presentation/) | Retourneert de IPresentation-interface.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/masternotesslide/header_footer_manager/) | Retourneert de HeaderFooter-beheerder van de masteropmerkingsdia.<br/>            Alleen-lezen [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/masternotesslide/theme_manager/) | Retourneert de themabeheerder.<br/>            Alleen-lezen [`IMasterThemeManager`](/slides/python-net/nl/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/nl/aspose.slides/masternotesslide/notes_style/) | Retourneert de stijl van een notitietekst.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/nl/aspose.slides/masternotesslide/drawing_guides/) | Retourneert een collectie van tekengidsen voor de masteropmerkingsdia.<br/>            Alleen-lezen [`IDrawingGuidesCollection`](/slides/python-net/nl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/nl/aspose.slides/masternotesslide/slide/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele vormen. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/masternotesslide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            Retournerende waarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId en dynamische inhoud, bijv. de huidige datumwaarde in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/masternotesslide/create_theme_effective/#) | Retourneert een effectief thema voor deze dia. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Vindt de eerste instantie van een vorm met de opgegeven alternatieve tekst. |


### Zie ook
* klasse [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)
* klasse [`MasterNotesSlide`](/slides/python-net/nl/aspose.slides/masternotesslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)