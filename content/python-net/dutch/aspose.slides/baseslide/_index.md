---
title: BaseSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/baseslide/
---
## BaseSlide klasse

Stelt gemeenschappelijke gegevens voor alle dia-typen voor.

Het BaseSlide-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/baseslide/shapes/) | Retourneert de vormen van een dia.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/baseslide/controls/) | Retourneert de verzameling ActiveX-besturingselementen op een dia.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/baseslide/name/) | Retourneert of stelt de naam van een dia in.<br/>            Lezen/schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/baseslide/slide_id/) | Retourneert de ID van een dia.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/baseslide/custom_data/) | Retourneert de aangepaste gegevens van de dia.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/baseslide/timeline/) | Retourneert het animatietijdlijnobject.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/baseslide/slide_show_transition/) | Retourneert het Transition-object dat informatie bevat over<br/>            hoe de opgegeven dia vordert tijdens een diavoorstelling.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/baseslide/background/) | Retourneert de achtergrond van de dia.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/baseslide/hyperlink_queries/) | Biedt gemakkelijke toegang tot de opgenomen hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/baseslide/show_master_shapes/) | Specificeert of vormen op de master-dia al dan niet op dia's worden weergegeven.<br/>            Voor de master-dia zelf geeft deze eigenschap altijd `false` terug.<br/>            Lezen/schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/baseslide/presentation/) | Retourneert de IPresentation-interface.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/nl/aspose.slides/baseslide/slide/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele vormen. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/baseslide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, zoals SlideId, en dynamische inhoud, zoals de huidige datwaarde in een Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/baseslide/create_theme_effective/#) | Retourneert een effectief thema voor deze dia. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Vindt de eerste instantie van een vorm met de opgegeven alternatieve tekst. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)