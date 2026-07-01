---
title: Hyperlink
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en hyperlink.
type: docs
weight: 5100
url: /sv/aspose.slides/hyperlink/
---
## Hyperlink klass

Representerar en hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Skapar en instans av en hyperlink som pekar på en specifik bild. Obs! den skapade hyperlinken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Skapar en instans av en hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Skapar en instans av en hyperlink med en annan hyperlink som källa och åsidosätter sekundära egenskaper. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Returnerar en hyperlink som avslutar föreställningen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Returnerar en hyperlink till den första bilden i presentationen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Returnerar en hyperlink till den sista bilden i presentationen. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Returnerar en hyperlink till den senast visade bilden. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Returnerar en speciell "play mediafile"-hyperlink. Används i AudioFrame och VideoFrame. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Returnerar en hyperlink till nästa bild. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Returnerar en speciell "do nothing"-hyperlink. Skrivskyddad [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Returnerar en hyperlink till föregående bild. Skrivskyddad [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Returnerar typ av Hyperlink:s åtgärd. Skrivskyddad [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Gör det möjligt att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representerar källan för hyperlink-färg – antingen stilar eller delformat. Läs/skriv [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Anger den externa URL:en. Skrivskyddad String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Representerar en hyperlink som är inställd för detta avsnitt utan hänsyn till avsnittets faktiska innehåll. PowerPoint beter sig speciellt för länkar och deras motsvarande text i ett avsnitt. Det möjliggör att skapa text för hyperlinken i form av en giltig URL, som skiljer sig från länkens verkliga adress. I så fall, när du visar länken i redigeringsfönstret, kommer den att ändras så att den matchar textavsnittet. Denna egenskap representerar hyperlinkens ursprungliga värde. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestämmer om hyperlinken ska markeras vid klick. Läs/skriv Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestämmer om målet för den överordnade hyperlinken ska läggas till i en lista över visade hyperlinks när den anropas. Läs/skriv Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Representerar uppspelning av ljud för hyperlinken. Läs/skriv [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestämmer om ljudet ska stoppas vid klick på hyperlinken. Läs/skriv Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Returnerar ramen inom den överordnade HTML-frameseten för målet för den överordnade hyperlinken när den finns. Läs/skriv String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Om Hyperlink pekar på en specifik bild returneras denna bild. Skrivskyddad [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Returnerar strängen som kan visas i ett användargränssnitt som är associerad med den överordnade hyperlinken. Läs/skriv String. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Avgör om de två Hyperlink-instanserna är lika. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Avgör om de två Hyperlink-instanserna är lika. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Fungerar som en hash-funktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testar två hyperlinks för likhet. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testar två hyperlinks för olikhet. |

### Se även

* klass [PVIObject](../pviobject)
* gränssnitt [IHyperlink](../ihyperlink)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->