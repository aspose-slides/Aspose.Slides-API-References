---
title: Hyperlink
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en hyperlänk.
type: docs
weight: 5120
url: /sv/aspose.slides/hyperlink/
---
## Hyperlink klass

Representerar en hyperlänk.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Skapar en instans av en hyperlänk som pekar på en specifik bild. Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Skapar en instans av en hyperlänk. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Skapar en instans av en hyperlänk med en annan hyperlänk som källa, och åsidosätter sekundära egenskaper. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Returnerar en hyperlänk som avslutar föreställningen. Endast läsning [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Returnerar en hyperlänk till den första bilden i presentationen. Endast läsning [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Returnerar en hyperlänk till den sista bilden i presentationen. Endast läsning [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Returnerar en hyperlänk till den senast visade bilden. Endast läsning [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Returnerar en speciell ”play mediafile”-hyperlänk. Används i AudioFrame och VideoFrame. Endast läsning [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Returnerar en hyperlänk till nästa bild. Endast läsning [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Returnerar en speciell ”do nothing”-hyperlänk. Endast läsning [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Returnerar en hyperlänk till föregående bild. Endast läsning [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Returnerar typen av Hyperlink-åtgärd. Endast läsning [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Endast läsning [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representerar källan för hyperlänkens färg – antingen stilar eller delformat. Läs/skriv [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Anger den externa URL-en. Endast läsning Sträng. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Representerar en hyperlänk som är inställd för den här delen utan hänsyn till delens faktiska innehåll. PowerPoint beter sig speciellt för länkar och motsvarande text i en del. Det möjliggör att skapa text för hyperlänken i form av en giltig URL, annorlunda än den verkliga adressen för länken. I detta fall, när du visar länken i redigeringsfönstret, kommer den att ändras för att matcha textdelen. Denna egenskap representerar hyperlänkens ursprungliga värde. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestämmer om hyperlänken ska markeras vid klick. Läs/skriv Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när det anropas. Läs/skriv Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Representerar uppspelning av ljud för hyperlänken. Läs/skriv [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestämmer om ljudet ska stoppas vid hyperlänksklick. Läs/skriv Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Returnerar ramen inom den överordnade HTML-frameset-en för målet för den överordnade hyperlänken när en sådan finns. Läs/skriv Sträng. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Om Hyperlink pekar på en specifik bild returnerar den här bilden. Endast läsning [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Returnerar strängen som kan visas i ett användargränssnitt i samband med den överordnade hyperlänken. Läs/skriv Sträng. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestämmer om de två Hyperlink-instanserna är lika. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestämmer om de två Hyperlink-instanserna är lika. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Fungerar som en hash-funktion för en specifik typ, lämplig för användning i hash-algoritmer och datastrukturer såsom en hashtabell. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testar två hyperlänkar för likhet. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testar två hyperlänkar för ojämlikhet. |

### Se även

* klass [PVIObject](../pviobject)
* gränssnitt [IHyperlink](../ihyperlink)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->