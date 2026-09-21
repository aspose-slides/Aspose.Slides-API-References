---
title: IHyperlink class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ihyperlink/
---
## IHyperlink klasse

Stelt een hyperlink voor.

Het type IHyperlink maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`action_type`](/slides/python-net/nl/aspose.slides/ihyperlink/action_type/) | Geeft het type van de actie van HyperLinkEx terug.<br/>            Alleen-lezen [`HyperlinkActionType`](/slides/python-net/nl/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/nl/aspose.slides/ihyperlink/external_url/) | Specificeert de externe URL<br/>            Als deze eigenschap niet None wordt, wordt eigenschap TargetSlide None.<br/>            Alleen-lezen **str**. |
| [`external_url_original`](/slides/python-net/nl/aspose.slides/ihyperlink/external_url_original/) | Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte.<br/>            <br/>            PowerPoint gedraagt zich specifiek voor koppelingen en de overeenkomende tekst in een gedeelte. Het maakt het mogelijk om tekst voor de hyperlink te maken in de vorm van een geldige URL, verschillend van het echte adres van de koppeling. In dit geval, wanneer je de koppeling bekijkt in het bewerkingsvenster, zal deze worden aangepast om overeen te komen met het tekstgedeelte. Deze eigenschap vertegenwoordigt de oorspronkelijke waarde van de hyperlink. |
| [`target_slide`](/slides/python-net/nl/aspose.slides/ihyperlink/target_slide/) | Als de HyperlinkEx een specifieke dia target, wordt deze dia geretourneerd.<br/>            Als deze eigenschap niet None wordt, wordt eigenschap ExternalUrl None.<br/>            Alleen-lezen [`ISlide`](/slides/python-net/nl/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/nl/aspose.slides/ihyperlink/target_frame/) | Geeft het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink terug wanneer er één bestaat.<br/>            Lezen/Schrijven **str**. |
| [`tooltip`](/slides/python-net/nl/aspose.slides/ihyperlink/tooltip/) | Geeft de tekenreeks terug die mogelijk in een gebruikersinterface wordt weergegeven als gekoppeld aan de bovenliggende hyperlink.<br/>            Lezen/Schrijven **str**. |
| [`history`](/slides/python-net/nl/aspose.slides/ihyperlink/history/) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst met bekeken hyperlinks wanneer deze wordt aangeroepen.<br/>            Lezen/Schrijven **bool**. |
| [`highlight_click`](/slides/python-net/nl/aspose.slides/ihyperlink/highlight_click/) | Bepaalt of de hyperlink moet worden gemarkeerd bij klikken.<br/>            Lezen/Schrijven **bool**. |
| [`stop_sound_on_click`](/slides/python-net/nl/aspose.slides/ihyperlink/stop_sound_on_click/) | Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik.<br/>            Lezen/Schrijven **bool**. |
| [`sound`](/slides/python-net/nl/aspose.slides/ihyperlink/sound/) | Stelt het afspelende geluid van de hyperlink voor.<br/>            Lezen/Schrijven [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/nl/aspose.slides/ihyperlink/color_source/) | Stelt de bron van hyperlinkkleur voor - ofwel stijlen of gedeelte-indeling.<br/>            Lezen/Schrijven [`HyperlinkColorSource`](/slides/python-net/nl/aspose.slides/hyperlinkcolorsource). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/nl/aspose.slides/ihyperlink/equals/#ihyperlink) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)