---
title: Hyperlink class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/hyperlink/
---
## Hyperlink-klass

Representerar en hyperlänk.

**Arv:**[`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

Hyperlink-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/sv/aspose.slides/hyperlink/__init__/#str) | Skapar en instans av en hyperlänk. |
| [`__init__(self, slide)`](/slides/python-net/sv/aspose.slides/hyperlink/__init__/#islide) | Skapar en instans av en hyperlänk som pekar på en specifik bild.<br/>            Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/sv/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Skapar en instans av en hyperlänk med en annan hyperlänk som källa och åsidosätter sekundära egenskaper. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`no_action`](/slides/python-net/sv/aspose.slides/hyperlink/no_action/) | Returnerar en speciell "gör ingenting"-hyperlänk.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/sv/aspose.slides/hyperlink/media/) | Returnerar en speciell "spela mediafil"-hyperlänk. Används i AudioFrame och VideoFrame.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/sv/aspose.slides/hyperlink/next_slide/) | Returnerar en hyperlänk till nästa bild.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/sv/aspose.slides/hyperlink/previous_slide/) | Returnerar en hyperlänk till föregående bild.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/sv/aspose.slides/hyperlink/first_slide/) | Returnerar en hyperlänk till den första bilden i presentationen.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/sv/aspose.slides/hyperlink/last_slide/) | Returnerar en hyperlänk till den sista bilden i presentationen.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/sv/aspose.slides/hyperlink/last_vieved_slide/) | Returnerar en hyperlänk till den senast visade bilden.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/sv/aspose.slides/hyperlink/end_show/) | Returnerar en hyperlänk som avslutar föreställningen.<br/>            Skrivskyddad [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/sv/aspose.slides/hyperlink/action_type/) | Returnerar typen av Hyperlink-åtgärden.<br/>            Skrivskyddad [`HyperlinkActionType`](/slides/python-net/sv/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/sv/aspose.slides/hyperlink/external_url/) | Anger den externa URL:en.<br/>            Skrivskyddad **str**. |
| [`target_slide`](/slides/python-net/sv/aspose.slides/hyperlink/target_slide/) | Om Hyperlink pekar på en specifik bild returneras den bilden.<br/>            Skrivskyddad [`ISlide`](/slides/python-net/sv/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/sv/aspose.slides/hyperlink/external_url_original/) | Representerar en hyperlänk som är inställd för detta segment utan hänsyn till segmentets faktiska innehåll.<br/>            <br/>            PowerPoint beter sig speciellt för länkar och deras motsvarande text i ett segment. Det tillåter att skapa text för hyperlänken i<br/>            form av en giltig URL, skild från länken verkliga adress. I detta fall, när du visar länken i redigeringsfönstret, kommer den att<br/>            ändras för att matcha textsegmentet. Denna egenskap representerar hyperlänkens originalvärde. |
| [`target_frame`](/slides/python-net/sv/aspose.slides/hyperlink/target_frame/) | Returnerar ramen inom det överordnade HTML-ramsetet för målet<br/>            för den överordnade hyperlänken när en sådan finns.<br/>            Läs/skriv **str**. |
| [`tooltip`](/slides/python-net/sv/aspose.slides/hyperlink/tooltip/) | Returnerar strängen som kan visas i ett användargränssnitt<br/>            som associerad med den överordnade hyperlänken.<br/>            Läs/skriv **str**. |
| [`history`](/slides/python-net/sv/aspose.slides/hyperlink/history/) | Bestämmer om målet för den överordnade hyperlänken ska läggas till<br/>            i en lista över visade hyperlänkar när den anropas.<br/>            Läs/skriv **bool**. |
| [`highlight_click`](/slides/python-net/sv/aspose.slides/hyperlink/highlight_click/) | Bestämmer om hyperlänken ska markeras vid klick.<br/>            Läs/skriv **bool**. |
| [`stop_sound_on_click`](/slides/python-net/sv/aspose.slides/hyperlink/stop_sound_on_click/) | Bestämmer om ljudet ska stoppas vid hyperlänk-klick.<br/>            Läs/skriv **bool**. |
| [`sound`](/slides/python-net/sv/aspose.slides/hyperlink/sound/) | Representerar det spelande ljudet för hyperlänken.<br/>            Läs/skriv [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/sv/aspose.slides/hyperlink/color_source/) | Representerar källan för hyperlänkens färg – antingen stilar eller segmentformat.<br/>            Läs/skriv [`HyperlinkColorSource`](/slides/python-net/sv/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/sv/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/hyperlink/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/sv/aspose.slides/hyperlink/equals/#ihyperlink) | Bestämmer om de två Hyperlink-instanserna är lika. |

### Se även
* klass [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)