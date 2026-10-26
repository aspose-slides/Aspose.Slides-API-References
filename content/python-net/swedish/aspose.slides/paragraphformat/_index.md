---
title: ParagraphFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/paragraphformat/
---
## ParagraphFormat klass

Denna klass innehåller egenskaperna för styckeformatering. Till skillnad från [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/sv/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

Typen ParagraphFormat exponerar följande medlemmar:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/paragraphformat/__init__/#) | Initialiserar en ny instans av [`ParagraphFormat`](/slides/python-net/sv/aspose.slides/paragraphformat) klass. |

## Egenskap | Beskrivning
| :- | :- |
| [`alignment`](/slides/python-net/sv/aspose.slides/paragraphformat/alignment/) | Returnerar eller anger textjusteringen i ett stycke utan arv.<br/>            Läs/skriv [`TextAlignment`](/slides/python-net/sv/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/sv/aspose.slides/paragraphformat/space_within/) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt - storlek i punkter. Inget arv tillämpas.<br/>            Läs/skriv **float**. |
| [`space_before`](/slides/python-net/sv/aspose.slides/paragraphformat/space_before/) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv.<br/>            Ett positivt värde anger procentandelen av teckenstorleken som det vita utrymmet ska vara.<br/>            Ett negativt värde anger storleken på det vita utrymmet i punktstorlek.<br/>            Läs/skriv **float**. |
| [`space_after`](/slides/python-net/sv/aspose.slides/paragraphformat/space_after/) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv.<br/>            Ett positivt värde anger procentandelen av teckenstorleken som det vita utrymmet ska vara.<br/>            Ett negativt värde anger storleken på det vita utrymmet i punktstorlek.<br/>            Läs/skriv **float**. |
| [`east_asian_line_break`](/slides/python-net/sv/aspose.slides/paragraphformat/east_asian_line_break/) | Avgör om radbrytning för Östasiatiskt språk används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/sv/aspose.slides/paragraphformat/right_to_left/) | Avgör om skrivning från höger till vänster används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/sv/aspose.slides/paragraphformat/latin_line_break/) | Avgör om radbrytning för latinska tecken används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/sv/aspose.slides/paragraphformat/hanging_punctuation/) | Avgör om hängande interpunktion används i ett stycke. Inget arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/sv/aspose.slides/paragraphformat/margin_left/) | Returnerar eller anger vänstermarginalen i ett stycke utan arv.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/paragraphformat/margin_right/) | Returnerar eller anger högermarginalen i ett stycke utan arv.<br/>            Läs/skriv **float**. |
| [`indent`](/slides/python-net/sv/aspose.slides/paragraphformat/indent/) | Returnerar eller anger styckets första radindragning/hängande indragning utan arv. Hängande indragning kan definieras med negativa värden.<br/>            Läs/skriv **float**. |
| [`default_tab_size`](/slides/python-net/sv/aspose.slides/paragraphformat/default_tab_size/) | Returnerar eller anger standardtabuleringsstorlek utan arv.<br/>            Läs/skriv **float**. |
| [`tabs`](/slides/python-net/sv/aspose.slides/paragraphformat/tabs/) | Returnerar tabbningar i ett stycke. Inget arv tillämpas.<br/>            Endast läs [`ITabCollection`](/slides/python-net/sv/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/sv/aspose.slides/paragraphformat/font_alignment/) | Returnerar eller anger en teckenjustering i ett stycke utan arv.<br/>            Läs/skriv [`FontAlignment`](/slides/python-net/sv/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/sv/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/sv/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/sv/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/sv/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metod | Beskrivning
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/paragraphformat/get_effective/#) | Hämtar effektiva styckeformateringsdata med arv tillämpat. |

### Anmärkningar

Denna klass används för att returnera och manipulera styckeformateringsegenskaper som definierats för det specifika stycket. Detta betyder att
            ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparameter-värdena inklusive ärvt måste du använda [`ParagraphFormat.get_effective`](/slides/python-net/sv/aspose.slides/paragraphformat/get_effective)-metoden 
            som returnerar en [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata)-instans.

### Se även
* klass [`IParagraphFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iparagraphformateffectivedata)
* klass [`ParagraphFormat`](/slides/python-net/sv/aspose.slides/paragraphformat)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)