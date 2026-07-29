---
title: LookupPrefix()
second_title: Aspose.Slides för C++ API-referens
description: Hittar prefixet som deklarerats för den givna namnrymdens URI.
type: docs
weight: 131
url: /sv/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) metod


Hittar prefixet som deklarerats för den givna namnrymdens URI.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Namnrymden att lösa för prefixet. |

### Returvärde

Det matchande prefixet. Om det inte finns något mappat prefix returnerar metoden [String::Empty](../../../system/string/empty/). Om ett null-värde tillhandahålls returneras **nullptr**.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNamespaceManager](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)