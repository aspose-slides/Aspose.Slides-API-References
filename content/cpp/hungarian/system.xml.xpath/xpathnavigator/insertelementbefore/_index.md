---
title: InsertElementBefore()
second_title: Aspose.Slides C++ API Referenciája
description: Új testvér elemet hoz létre a jelenlegi csomópont előtt a megadott névtér előtag, helyi név és névtér URI felhasználásával, a megadott értékkel.
type: docs
weight: 1015
url: /hu/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) metódus

Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | A új gyermek elem névtér előtagja (ha van). |
| localName | [String](../../../system/string/) | Az új gyermek elem helyi neve (ha van). |
| namespaceURI | [String](../../../system/string/) | Az új gyermek elem névtér URI-je (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** egyenlő. |
| value | [String](../../../system/string/) | Az új gyermek elem értéke. Ha [String::Empty](../../../system/string/empty/) vagy **nullptr** kerül átadásra, egy üres elem jön létre. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névtere [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)