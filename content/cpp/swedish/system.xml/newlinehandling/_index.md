---
title: NewLineHandling
second_title: Aspose.Slides för C++ API-referens
description: Anger hur radbrytningar ska hanteras.
type: docs
weight: 690
url: /sv/system.xml/newlinehandling/
---
## NewLineHandling enum


Anger hur radbrytningar ska hanteras.

```cpp
enum class NewLineHandling
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Replace | 0 | Radbrytningstecken ersätts för att matcha det tecken som anges i [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/)-värdet. |
| Entitize | 1 | Radbrytningstecken entitiseras. Denna inställning bevarar alla tecken när utskriften läses av en normaliserande [XmlReader](../xmlreader/). |
| None | 2 | Radbrytningstecknen är oförändrade. Utskriften är densamma som inmatningen. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)