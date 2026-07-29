---
title: DtdProcessing
second_title: Aspose.Slides för C++ API-referens
description: Anger alternativen för behandling av DTD:er. Uppräkningen DtdProcessing används av klassen XmlReaderSettings.
type: docs
weight: 638
url: /sv/system.xml/dtdprocessing/
---
## DtdProcessing enum

Anger alternativen för behandling av DTD. Uppräkningen DtdProcessing används av [XmlReaderSettings](../xmlreadersettings/)-klassen.

```cpp
enum class DtdProcessing
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Prohibit | 0 | Anger att när en DTD påträffas, kastas ett XmlException med ett meddelande som säger att DTD:er är förbjudna. Detta är standardbeteendet. |
| Ignore | 1 | Gör att DOCTYPE-elementet ignoreras. Ingen DTD-behandling sker, och DTD/DOCTYPE försvinner i utskriften. |
| Parse | 2 | Används för att analysera DTD:er. |

## Se också

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)