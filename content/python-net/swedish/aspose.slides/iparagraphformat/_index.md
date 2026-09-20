---
title: IParagraphFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iparagraphformat/
---
## IParagraphFormat klass

Denna klass innehåller paragrafformateringsegenskaperna. Till skillnad från [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

IParagraphFormat-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`bullet`](/slides/python-net/sv/aspose.slides/iparagraphformat/bullet/) | Returnerar punktformat för stycket.<br/>            Skrivskyddad [`IBulletFormat`](/slides/python-net/sv/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/sv/aspose.slides/iparagraphformat/depth/) | Returnerar eller anger djupet för stycket.<br/>            Värde 0 betyder odefinierat värde.<br/>            Läs/skriv **int**. |
| [`alignment`](/slides/python-net/sv/aspose.slides/iparagraphformat/alignment/) | Returnerar eller anger textjusteringen i ett stycke utan arv.<br/>            Läs/skriv [`TextAlignment`](/slides/python-net/sv/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/sv/aspose.slides/iparagraphformat/space_within/) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Inget arv tillämpas.<br/>            Läs/skriv **float**. |
| [`space_before`](/slides/python-net/sv/aspose.slides/iparagraphformat/space_before/) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv.<br/>            Ett positivt värde anger hur stor procentandel av teckenstorleken det vita utrymmet ska vara.<br/>            Ett negativt värde anger storleken på det vita utrymmet i punktstorlek.<br/>            Läs/skriv **float**. |
| [`space_after`](/slides/python-net/sv/aspose.slides/iparagraphformat/space_after/) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv.<br/>            Ett positivt värde anger hur stor procentandel av teckenstorleken det vita utrymmet ska vara.<br/>            Ett negativt värde anger storleken på det vita utrymmet i punktstorlek.<br/>            Läs/skriv **float**. |
| [`east_asian_line_break`](/slides/python-net/sv/aspose.slides/iparagraphformat/east_asian_line_break/) | Avgör om radbrytning för östasiatiskt språk används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/sv/aspose.slides/iparagraphformat/right_to_left/) | Avgör om höger-till-vänster-skrivning används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/sv/aspose.slides/iparagraphformat/latin_line_break/) | Avgör om latinisk radbrytning används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/sv/aspose.slides/iparagraphformat/hanging_punctuation/) | Avgör om hängande skiljetecken används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/sv/aspose.slides/iparagraphformat/margin_left/) | Returnerar eller anger vänstermarginalen i ett stycke utan arv.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/iparagraphformat/margin_right/) | Returnerar eller anger högermarginalen i ett stycke utan arv.<br/>            Läs/skriv **float**. |
| [`indent`](/slides/python-net/sv/aspose.slides/iparagraphformat/indent/) | Returnerar eller anger paragrafens första rad-indrag/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden.<br/>            Läs/skriv **float**. |
| [`default_tab_size`](/slides/python-net/sv/aspose.slides/iparagraphformat/default_tab_size/) | Returnerar eller anger standardtabulatorstorlek utan arv.<br/>            Läs/skriv **float**. |
| [`tabs`](/slides/python-net/sv/aspose.slides/iparagraphformat/tabs/) | Returnerar tabulatorer för ett stycke. Inget arv tillämpas.<br/>            Skrivskyddad [`ITabCollection`](/slides/python-net/sv/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/sv/aspose.slides/iparagraphformat/font_alignment/) | Returnerar eller anger en teckensnittsjustering i ett stycke utan arv.<br/>            Läs/skriv [`FontAlignment`](/slides/python-net/sv/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/sv/aspose.slides/iparagraphformat/default_portion_format/) | Returnerar standarddelformat för ett stycke. Inget arv tillämpas.<br/>            Skrivskyddad [`IPortionFormat`](/slides/python-net/sv/aspose.slides/iportionformat). |

## Metoder

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/iparagraphformat/get_effective/#) | Hämtar effektiv paragrafformateringsdata med arv tillämpat. |


### Anmärkningar

Denna klass används för att returnera och manipulera paragrafformateringsegenskaper som definierats för det specifika stycket. Det innebär att
            inget arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".


För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [`IParagraphFormat.get_effective`](/slides/python-net/sv/aspose.slides/iparagraphformat/get_effective)-metoden 
            som returnerar en [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata)-instans.

### Se även
* klass [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)