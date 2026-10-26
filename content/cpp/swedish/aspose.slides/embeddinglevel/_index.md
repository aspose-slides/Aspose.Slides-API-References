---
title: EmbeddingLevel
second_title: Aspose.Slides för C++ API-referens
description: Representerar licensrättigheterna för att bädda in teckensnittet.
type: docs
weight: 5786
url: /sv/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Representerar licensrättigheterna för att bädda in teckensnittet.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) med den här inställningen indikerar att de kan bäddas in och permanent installeras på det fjärranslutna systemet av en applikation. Användaren av det fjärranslutna systemet får samma rättigheter, förpliktelser och licenser för det teckensnittet som den ursprungliga köparen av teckensnittet, och omfattas av samma slutbrukarlicensavtal, upphovsrätt, designpatent och/eller varumärke som den ursprungliga köparen. |
| Restricted | 2 | [Fonts](../fonts/) som endast har denna bit satt får inte modifieras, bäddas in eller bytas på något sätt utan att först inhämta tillstånd från den lagliga ägaren. |
| PreviewPrint | 4 | När denna bit är satt kan teckensnittet bäddas in och tillfälligt laddas på det fjärranslutna systemet. Dokument som innehåller Preview & Print fonts måste öppnas \"read-only;\" och inga ändringar kan göras i dokumentet. |
| Editable | 8 | När denna bit är satt kan teckensnittet bäddas in men får endast installeras tillfälligt på andra system. Till skillnad från Preview & Print fonts får dokument som innehåller Editable fonts öppnas för läsning, redigering är tillåten och ändringar kan sparas. |
| NoSubsetting | 256 | När denna bit är satt får teckensnittet inte subsettas innan inbäddning. Andra inbäddningsrestriktioner som specificerats i bitarna 0-3 och 9 gäller också. |
| BitmapOnly | 512 | När denna bit är satt får endast bitmaps som finns i teckensnittet bäddas in. Ingen konturdata får inbäddas. Om det inte finns några bitmaps tillgängliga i teckensnittet anses teckensnittet vara icke-inbäddningsbart och inbäddningstjänsterna kommer att misslyckas. |

## Se även

* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)