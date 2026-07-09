---
title: ParagraphFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller styckeformateringsegenskaper. Till skillnad från IParagraphFormatEffectiveData./iparagraphformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 9310
url: /sv/aspose.slides/paragraphformat/
---
## ParagraphFormat klass

Denna klass innehåller egenskaper för styckeformatering. Till skillnad från [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initierar en ny instans av [`ParagraphFormat`](../paragraphformat) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Läs-endast [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Returnerar eller anger standardtabuleringsstorlek utan arv. Läs/skriv Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bestämmer om radbrytning för östasiatiska språk används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Returnerar eller anger teckensnittjustering i ett stycke utan arv. Läs/skriv [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bestämmer om hängande interpunktion används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Returnerar eller anger första rad-indrag/hängande indrag i ett stycke utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bestämmer om latinsk radbrytning används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bestämmer om höger-till-vänster-skrivning används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankutrymmet ska motsvara. Ett negativt värde anger storleken på blankutrymmet i punkter. Läs/skriv Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankutrymmet ska motsvara. Ett negativt värde anger storleken på blankutrymmet i punkter. Läs/skriv Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Inget arv tillämpas. Läs/skriv Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Returnerar tabuleringar för ett stycke. Inget arv tillämpas. Läs-endast [`ITabCollection`](../itabcollection). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med angivet objekt. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Hämtar effektiv styckeformateringsdata med arv tillämpat. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hash-kod. |

### Anmärkningar

Denna klass används för att returnera och manipulera styckeformateringsegenskaper definierade för det specifika stycket. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få effektiva formateringsparametervärden inklusive ärvda måste du använda [`GetEffective`](./geteffective)-metoden som returnerar en [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-instans.

### Se också

* klass [PVIObject](../pviobject)
* gränssnitt [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* gränssnitt [IParagraphFormat](../iparagraphformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->