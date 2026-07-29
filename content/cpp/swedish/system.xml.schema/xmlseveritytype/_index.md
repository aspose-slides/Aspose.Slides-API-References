---
title: XmlSeverityType
second_title: Aspose.Slides för C++ API-referens
description: Representerar allvaret av valideringshändelsen.
type: docs
weight: 1080
url: /sv/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Representerar allvaret av valideringshändelsen.

```cpp
enum class XmlSeverityType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Error | 0 | Indikerar att ett valideringsfel uppstod när instansdokumentet validerades. Detta gäller dokumenttypdefinitioner (DTDs) och XML [Schema](../) definition language (XSD) scheman. World Wide [Web](../../system.web/) Consortium (W3C) giltighetsrestriktioner betraktas som fel. Om ingen valideringshändelsehanterare har skapats, kastar fel ett undantag. |
| Warning | 1 | Indikerar att en valideringshändelse inträffade som inte är ett fel. En varning utfärdas vanligtvis när det inte finns någon DTD, eller XML [Schema](../) för att validera ett särskilt element eller attribut mot. Till skillnad från fel, kastar varningar inte ett undantag om det inte finns någon valideringshändelsehanterare. |

## Se även

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)