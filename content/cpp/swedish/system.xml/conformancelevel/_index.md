---
title: ConformanceLevel
second_title: Aspose.Slides för C++ API-referens
description: Anger hur mycket in- eller utdatakontroll som XmlReader och XmlWriter-objekt utför.
type: docs
weight: 625
url: /sv/system.xml/conformancelevel/
---
## ConformanceLevel enum

Anger mängden in- eller utdata-kontroll som [XmlReader](../xmlreader/) och [XmlWriter](../xmlwriter/) objekt utför.

```cpp
enum class ConformanceLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/)- eller [XmlWriter](../xmlwriter/)-objektet upptäcker automatiskt om dokument-nivå eller fragment-nivå kontroll ska utföras, och gör den lämpliga kontrollen. Om du kapslar in ett annat [XmlReader](../xmlreader/)- eller [XmlWriter](../xmlwriter/)-objekt, utför det yttre objektet ingen ytterligare konformitetskontroll. Konformitetskontrollen lämnas till det underliggande objektet. |
| Fragment | 1 | XML-data är ett [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), enligt W3C:s definition. Denna konformitetsnivå representerar ett XML-dokument som kanske saknar ett rotnod men annars är väl bildat. Denna kontrollnivå säkerställer att strömmen som läses eller skrivs kan konsumeras av någon processor som ett [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | XML-data följer reglerna för ett välformat [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), enligt W3C:s definition. Denna kontrollnivå säkerställer att strömmen som läses eller skrivs kan konsumeras av någon processor som ett [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Se också

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)