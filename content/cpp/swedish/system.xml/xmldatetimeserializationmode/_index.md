---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides för C++ API-referens
description: Anger hur tidvärdet ska behandlas när det konverteras mellan sträng och DateTime.
type: docs
weight: 781
url: /sv/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Anger hur tidvärdet ska behandlas när det konverteras mellan sträng och [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Local | 0 | Behandla som lokal tid. Om [DateTime](../../system/datetime/)-objektet representerar en Coordinated Universal Time (UTC) konverteras det till lokal tid. |
| Utc | 1 | Behandla som en UTC. Om [DateTime](../../system/datetime/)-objektet representerar en lokal tid konverteras det till en UTC. |
| Unspecified | 2 | Behandla som lokal tid om en [DateTime](../../system/datetime/) konverteras till en sträng. Om en sträng konverteras till [DateTime](../../system/datetime/) konverteras den till lokal tid om en tidszon har angetts. |
| RoundtripKind | 3 | Tidszoninformation bör bevaras vid konvertering. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)