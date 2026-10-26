---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy attribútumcsomópontot az aktuális elemcsomóponton a megadott névtér előtag, helyi név és névtér URI használatával a megadott értékkel.
type: docs
weight: 1041
url: /hu/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metódus

Létrehoz egy attribútumcsomópontot az aktuális elemcsomóponton a megadott névtér előtag, helyi név és névtér URI használatával a megadott értékkel.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Az új attribútumcsomópont névtér előtagja (ha van). |
| localName | [String](../../../system/string/) | Az új attribútumcsomópont helyi neve, amely nem lehet [String::Empty](../../../system/string/empty/) vagy **nullptr**. |
| namespaceURI | [String](../../../system/string/) | Az új attribútumcsomópont névtér URI-ja (ha van). |
| value | [String](../../../system/string/) | Az új attribútumcsomópont értéke. Ha [String::Empty](../../../system/string/empty/) vagy **nullptr** kerül átadásra, egy üres attribútumcsomópont jön létre. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)