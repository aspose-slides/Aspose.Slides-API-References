---
title: GetAttribute()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a megadott helyi névvel és névtér URI-val rendelkező attribútum értékét.
type: docs
weight: 482
url: /hu/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) metódus


Visszaadja a megadott helyi névvel és névtér URI-val rendelkező attribútum értékét.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. **localName** nagy- és kisbetűre érzékeny. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

Egy [String](../../../system/string/), amely tartalmazza a megadott attribútum értékét; [String::Empty](../../../system/string/empty/), ha nem található megfelelő attribútum, vagy ha a [XPathNavigator](../) nem egy elemcsomóponton van pozícionálva.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névtere [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)