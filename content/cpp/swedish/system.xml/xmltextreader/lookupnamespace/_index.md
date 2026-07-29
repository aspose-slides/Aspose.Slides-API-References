---
title: LookupNamespace()
second_title: Aspose.Slides för C++ API-referens
description: Löser ett namnrymdsprefix i det aktuella elementets omfång.
type: docs
weight: 612
url: /sv/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) metod


Löser ett namnrymdsprefix i det aktuella elementets omfång.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet vars namnrymd-URI du vill lösa. För att matcha standardnamnrymden, skicka en tom sträng. Denna sträng behöver inte atomiseras. |

### Return Value

Namnrymdens URI som prefixet mappar till eller **nullptr** om ingen matchande prefix hittas.

## See Also

* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)