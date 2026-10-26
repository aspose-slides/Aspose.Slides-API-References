---
title: HandleRepeatedSpaces
second_title: Aspose.Slides för C++ API-referens
description: Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export.
type: docs
weight: 937
url: /sv/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export.

```cpp
enum class HandleRepeatedSpaces
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Alla mellanslag bevaras som vanliga mellanslagstecken utan några ändringar. Ingen transformation tillämpas, och flera på varandra följande mellanslag exporteras oförändrade. |
| AlternateSpacesToNbsp | 1 | Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att alternera mellan vanliga mellanslagstecken och icke-brytande mellanslag-entiteter (**&nbsp;**). Det första mellanslaget bevaras alltid som ett vanligt mellanslag. |
| MultipleSpacesToNbsp | 2 | Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att bevara det första mellanslaget som ett vanligt mellanslagstecken och ersätta alla efterföljande mellanslag med icke-brytande mellanslag-entiteter (**&nbsp;**). |

## Se också

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)