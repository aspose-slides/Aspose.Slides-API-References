---
title: IHyperlink class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ihyperlink/
---
## IHyperlink klass

Representerar en hyperlänk.

IHyperlink-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`action_type`](/slides/python-net/sv/aspose.slides/ihyperlink/action_type/) | Returnerar typ av HyperLinkEx:s åtgärd.<br/>            Skrivskyddad [`HyperlinkActionType`](/slides/python-net/sv/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/sv/aspose.slides/ihyperlink/external_url/) | Specificerar den externa URL<br/>            Om denna egenskap blir icke-None så blir egenskapen TargetSlide None.<br/>            Skrivskyddad **str**. |
| [`external_url_original`](/slides/python-net/sv/aspose.slides/ihyperlink/external_url_original/) | Representerar en hyperlänk som är inställd för denna del utan hänsyn till det faktiska innehållet i delen.<br/>            <br/>            PowerPoint beter sig specifikt för länkar och deras motsvarande text i en del. Den tillåter att skapa text för hyperlänken i<br/>            formen av en giltig URL, som skiljer sig från länken faktiska adress. I detta fall, när du ser länken i redigeringsfönstret, kommer den att<br/>            ändras för att matcha textdelen. Denna egenskap representerar hyperlänkens ursprungliga värde. |
| [`target_slide`](/slides/python-net/sv/aspose.slides/ihyperlink/target_slide/) | Om HyperlinkEx pekar på en specifik bild returnerar den här bilden.<br/>            Om egenskapen blir icke-None så blir egenskapen ExternalUrl None.<br/>            Skrivskyddad [`ISlide`](/slides/python-net/sv/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/sv/aspose.slides/ihyperlink/target_frame/) | Returnerar ramen inom den överordnade HTML-ramuppsättningen för målet<br/>            för den överordnade hyperlänken när den finns.<br/>            Läs/skriv **str**. |
| [`tooltip`](/slides/python-net/sv/aspose.slides/ihyperlink/tooltip/) | Returnerar strängen som kan visas i ett användargränssnitt<br/>            som är knuten till den överordnade hyperlänken.<br/>            Läs/skriv **str**. |
| [`history`](/slides/python-net/sv/aspose.slides/ihyperlink/history/) | Bestämmer om målet för den överordnade hyperlänken ska läggas till<br/>            till en lista över visade hyperlänkar när den anropas.<br/>            Läs/skriv **bool**. |
| [`highlight_click`](/slides/python-net/sv/aspose.slides/ihyperlink/highlight_click/) | Bestämmer om hyperlänken ska markeras vid klick.<br/>            Läs/skriv **bool**. |
| [`stop_sound_on_click`](/slides/python-net/sv/aspose.slides/ihyperlink/stop_sound_on_click/) | Bestämmer om ljudet ska stoppas när hyperlänken klickas.<br/>            Läs/skriv **bool**. |
| [`sound`](/slides/python-net/sv/aspose.slides/ihyperlink/sound/) | Representerar det spelande ljudet för hyperlänken.<br/>            Läs/skriv [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/sv/aspose.slides/ihyperlink/color_source/) | Representerar källan till hyperlänkens färg – antingen stilar eller delformat.<br/>            Läs/skriv [`HyperlinkColorSource`](/slides/python-net/sv/aspose.slides/hyperlinkcolorsource). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/sv/aspose.slides/ihyperlink/equals/#ihyperlink) | Bestämmer om de två Hyperlink-instansen är lika. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)