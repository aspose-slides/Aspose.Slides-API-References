---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API-referencia
description: Új gyermekelemet hoz létre a jelenlegi csomópont gyermekcsomópontjainak listájának elején, a megadott névtér előtag, helyi név és névtér URI, valamint a megadott érték felhasználásával.
type: docs
weight: 989
url: /hu/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metódus

Új gyermekelemet hoz létre a jelenlegi csomópont gyermekcsomópontjainak listájának elején a megadott névtér előtag, helyi név és névtér URI, valamint a megadott érték felhasználásával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Az új gyermekelem névtér előtagja (ha van). |
| localName | [String](../../../system/string/) | Az új gyermekelem helyi neve (ha van). |
| namespaceURI | [String](../../../system/string/) | Az új gyermekelem névtér URI-ja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** egyenértékű. |
| value | [String](../../../system/string/) | Az új gyermekelem értéke. Ha [String::Empty](../../../system/string/empty/) vagy **nullptr** kerül átadásra, akkor egy üres elem jön létre. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)