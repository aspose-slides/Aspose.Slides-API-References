---
title: LookupNamespace()
second_title: Aspose.Slides för C++ API-referens
description: Löser en namnrymdsprefix i det aktuella elementets omfång.
type: docs
weight: 404
url: /sv/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) metod

Löser en namnrymdsprefix i det aktuella elementets omfång.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet vars namnrymd-URI du vill lösa. För att matcha standardnamnrymden, skicka en tom sträng. Denna sträng behöver inte atomiseras. |

### Returvärde

Namnrymd-URI:n som prefixet mappar till eller **nullptr** om ingen matchande prefix hittas.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)