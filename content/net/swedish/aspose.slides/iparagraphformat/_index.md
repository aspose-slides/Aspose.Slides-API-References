---
title: IParagraphFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller styckeformateringsegenskaperna. Till skillnad från IParagraphFormatEffectiveData./iparagraphformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 6610
url: /sv/aspose.slides/iparagraphformat/
---
## IParagraphFormat gränssnitt

Denna klass innehåller styckeformateringsegenskaperna. Till skillnad från [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public interface IParagraphFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Returnerar punktlistformat för stycket. Skrivskyddad [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Returnerar standarddelformat för ett stycke. Inget arv tillämpas. Skrivskyddad [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Returnerar eller anger standardtabulatorstorlek utan arv. Läs/skriv Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Returnerar eller anger djupet för stycket. Värdet 0 betyder odefinierat värde. Läs/skriv Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Avgör om radbrytning för Östasiatiskt språk används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Returnerar eller anger teckensnittjustering i ett stycke utan arv. Läs/skriv [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Avgör om hängande skiljetecken används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Returnerar eller anger styckets första rad indrag/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Avgör om radbrytning för latin används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Avgör om skrivet i riktning från höger till vänster används i ett stycke. Inget arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som mellanslaget ska vara. Ett negativt värde anger storleken på mellanslaget i punkter. Läs/skriv Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som mellanslaget ska vara. Ett negativt värde anger storleken på mellanslaget i punkter. Läs/skriv Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Inget arv tillämpas. Läs/skriv Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Returnerar tabulatorer för ett stycke. Inget arv tillämpas. Skrivskyddad [`ITabCollection`](../itabcollection). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Hämtar effektiv styckeformateringsdata med arv tillämpat. |

### Anmärkningar

Denna klass används för att returnera och manipulera styckeformateringsegenskaper som definierats för det specifika stycket. Detta innebär att inget arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda metoden [`GetEffective`](./geteffective) som returnerar en [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-instans.

### Se även

* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->