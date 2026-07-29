---
title: LinkEmbedDecision
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer hur objektet kommer att bearbetas vid sparning.
type: docs
weight: 911
url: /sv/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Bestämmer hur objektet ska bearbetas vid sparning.

```cpp
enum class LinkEmbedDecision
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Link | 0 | Objektet lagras externt och refereras via URL |
| Embed | 1 | Objektet bör bäddas in i en genererad fil om möjligt. Om inbäddning är omöjlig kommer GetUrl att anropas och, beroende på resultatet, kommer objektet att refereras med URL eller ignoreras. |
| Ignore | 2 | Objektet kommer att ignoreras. |

## Se även

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)