---
title: Hyperlink class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/hyperlink/
---
## Hyperlink klasse

Stelt een hyperlink voor.

**Erfenis:**[`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)

Het Hyperlink-type stelt de volgende leden beschikbaar:

## Constructoren

| Constructor | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/nl/aspose.slides/hyperlink/__init__/#str) | Maakt een instantie van een hyperlink aan. |
| [`__init__(self, slide)`](/slides/python-net/nl/aspose.slides/hyperlink/__init__/#islide) | Maakt een instantie van een hyperlink die naar een specifieke dia verwijst.<br/>            Opmerking: de gemaakte hyperlink moet worden toegewezen aan een object uit dezelfde presentatie, anders wordt de link opgeslagen als NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/nl/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`no_action`](/slides/python-net/nl/aspose.slides/hyperlink/no_action/) | Retourneert een speciale "do nothing" hyperlink.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/nl/aspose.slides/hyperlink/media/) | Retourneert een speciale "play mediafile" hyperlink. Wordt gebruikt in AudioFrame en VideoFrame.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/nl/aspose.slides/hyperlink/next_slide/) | Retourneert een hyperlink naar de volgende dia.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/nl/aspose.slides/hyperlink/previous_slide/) | Retourneert een hyperlink naar de vorige dia.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/nl/aspose.slides/hyperlink/first_slide/) | Retourneert een hyperlink naar de eerste dia van de presentatie.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/nl/aspose.slides/hyperlink/last_slide/) | Retourneert een hyperlink naar de laatste dia van de presentatie.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/nl/aspose.slides/hyperlink/last_vieved_slide/) | Retourneert een hyperlink naar de laatst bekeken dia.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/nl/aspose.slides/hyperlink/end_show/) | Retourneert een hyperlink die de presentatie beëindigt.<br/>            Alleen-lezen [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/nl/aspose.slides/hyperlink/action_type/) | Retourneert het type van de actie van de Hyperlink.<br/>            Alleen-lezen [`HyperlinkActionType`](/slides/python-net/nl/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/nl/aspose.slides/hyperlink/external_url/) | Specificeert de externe URL.<br/>            Alleen-lezen **str**. |
| [`target_slide`](/slides/python-net/nl/aspose.slides/hyperlink/target_slide/) | Als de Hyperlink naar een specifieke dia wijst, retourneert deze dia.<br/>            Alleen-lezen [`ISlide`](/slides/python-net/nl/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/nl/aspose.slides/hyperlink/external_url_original/) | Stelt een hyperlink voor die is ingesteld voor dit gedeelte zonder rekening te houden met de werkelijke inhoud van het gedeelte.<br/>            <br/>            PowerPoint gedraagt zich specifiek voor links en hun bijbehorende tekst in een gedeelte. Het maakt het mogelijk om tekst voor de hyperlink te maken in<br/>            de vorm van een geldige URL, verschillend van het daadwerkelijke adres van de link. In dit geval, wanneer u de link bekijkt in het bewerkingsvenster, zal deze<br/>            worden aangepast om overeen te komen met het tekstgedeelte. Deze eigenschap vertegenwoordigt de oorspronkelijke waarde van de hyperlink. |
| [`target_frame`](/slides/python-net/nl/aspose.slides/hyperlink/target_frame/) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel<br/>            van de bovenliggende hyperlink wanneer deze bestaat.<br/>            Lezen/Schrijven **str**. |
| [`tooltip`](/slides/python-net/nl/aspose.slides/hyperlink/tooltip/) | Retourneert de tekenreeks die mogelijk wordt weergegeven in een gebruikersinterface<br/>            als geassocieerd met de bovenliggende hyperlink.<br/>            Lezen/Schrijven **str**. |
| [`history`](/slides/python-net/nl/aspose.slides/hyperlink/history/) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd<br/>            aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen.<br/>            Lezen/Schrijven **bool**. |
| [`highlight_click`](/slides/python-net/nl/aspose.slides/hyperlink/highlight_click/) | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken.<br/>            Lezen/Schrijven **bool**. |
| [`stop_sound_on_click`](/slides/python-net/nl/aspose.slides/hyperlink/stop_sound_on_click/) | Bepaalt of het geluid moet worden gestopt bij het klikken op de hyperlink.<br/>            Lezen/Schrijven **bool**. |
| [`sound`](/slides/python-net/nl/aspose.slides/hyperlink/sound/) | Stelt het afspelende geluid van de hyperlink voor.<br/>            Lezen/Schrijven [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/nl/aspose.slides/hyperlink/color_source/) | Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-opmaak.<br/>            Lezen/Schrijven [`HyperlinkColorSource`](/slides/python-net/nl/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/nl/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/hyperlink/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/nl/aspose.slides/hyperlink/equals/#ihyperlink) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |

### Zie ook
* klasse [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink)
* klasse [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)