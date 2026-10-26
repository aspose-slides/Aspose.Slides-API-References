---
title: IBaseSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ibaseslide/
---
## IBaseSlide klasse

Representeert algemene gegevens voor alle dia-typen.

Het IBaseSlide-type biedt de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/ibaseslide/shapes/) | Geeft de vormen van een dia terug.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/ibaseslide/controls/) | Geeft de verzameling van ActiveX-besturingselementen op een dia terug.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/ibaseslide/name/) | Geeft de naam van een dia terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/ibaseslide/slide_id/) | Geeft de ID van een dia terug.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/ibaseslide/custom_data/) | Geeft de aangepaste gegevens van de dia terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/ibaseslide/timeline/) | Geeft het animatie-tijdlijnobject terug.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/ibaseslide/slide_show_transition/) | Geeft het TransitionEx-object dat informatie bevat over<br/>            hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/ibaseslide/background/) | Geeft de achtergrond van de dia terug.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/ibaseslide/hyperlink_queries/) | Biedt gemakkelijke toegang tot ingesloten hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/ibaseslide/show_master_shapes/) | Specificeert of vormen op de masterdia al dan niet op dia's worden getoond.<br/>            Voor de masterdia zelf geeft deze eigenschap altijd `false` terug.<br/>            Lezen/schrijven **bool**. |
| [`slide`](/slides/python-net/nl/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/ibaseslide/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Vindt de eerste vondst van een vorm met de opgegeven alternatieve tekst. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele vormen. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/ibaseslide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen enz. gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in een datum-placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)