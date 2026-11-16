---
title: Hyperlink
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en hyperlänk.
type: docs
weight: 5140
url: /sv/aspose.slides/hyperlink/
---
## Hyperlink-klass

Representerar en hyperlänk.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Skapar en instans av en hyperlänk som pekar på en specifik bild. Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Skapar en instans av en hyperlänk. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Skapar en instans av en hyperlänk med en annan hyperlänk som källa, och överskriver sekundära egenskaper. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Returnerar en hyperlänk som avslutar föreställningen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Returnerar en hyperlänk till den första bilden i presentationen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Returnerar en hyperlänk till den sista bilden i presentationen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Returnerar en hyperlänk till den senast visade bilden. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Returnerar en speciell "play mediafile"-hyperlänk. Används i AudioFrame och VideoFrame. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Returnerar en hyperlänk till nästa bild. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Returnerar en speciell "do nothing"-hyperlänk. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Returnerar en hyperlänk till föregående bild. Skrivskyddad [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Returnerar typen av Hyperlink-åtgärd. Skrivskyddad [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representerar källan för hyperlänkens färg – antingen stilar eller portionsformat. Läs/skriv [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Anger den externa URL-en. Skrivskyddad String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Representerar en hyperlänk som är inställd för denna del utan hänsyn till delens faktiska innehåll. PowerPoint hanterar länkar och deras motsvarande text i en del på ett speciellt sätt. Det möjliggör att skapa text för hyperlänken i form av en giltig URL, som skiljer sig från länkens faktiska adress. I så fall, när du visar länken i redigeringsfönstret, kommer den att ändras för att matcha textdelen. Denna egenskap representerar hyperlänkens ursprungliga värde. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestämmer om hyperlänken ska markeras vid klick. Läs/skriv Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. Läs/skriv Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Representerar uppspelningen av hyperlänkens ljud. Läs/skriv [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestämmer om ljudet ska stoppas vid hyperlänksklick. Läs/skriv Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Returnerar ramen inom den överordnade HTML-ramuppsättningen för målet för den överordnade hyperlänken när den finns. Läs/skriv String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Om Hyperlink pekar på en specifik bild returneras denna bild. Skrivskyddad [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Returnerar strängen som kan visas i ett användargränssnitt som associerad med den överordnade hyperlänken. Läs/skriv String. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestämmer om de två Hyperlink-instanserna är lika. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestämmer om de två Hyperlink-instanserna är lika. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Fungerar som en hash-funktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testar två hyperlänkar för jämlikhet. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testar två hyperlänkar för ojämlikhet. |

### Se också

* klass [PVIObject](../pviobject)
* gränssnitt [IHyperlink](../ihyperlink)
* namnutrymme [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->