---
title: AppendChildElement()
second_title: Aspose.Slides for C++ API-referencia
description: Létrehoz egy új gyermekelem csomópontot a jelenlegi csomópont gyermekcsomópontjainak listájának végén a megadott névtér előtag, helyi név és névtér URI segítségével, a megadott értékkel.
type: docs
weight: 1002
url: /hu/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metódus


Létrehoz egy új gyermekelem csomópontot a jelenlegi csomópont gyermekcsomópontjainak listájának végén a megadott névtér előtag, helyi név és névtér URI segítségével, a megadott értékkel.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Az új gyermekelem csomópont névtér előtagja (ha van). |
| localName | [String](../../../system/string/) | Az új gyermekelem csomópont helyi neve (ha van). |
| namespaceURI | [String](../../../system/string/) | Az új gyermekelem csomópont névtér URI-ja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** ekvivalens. |
| value | [String](../../../system/string/) | Az új gyermekelem csomópont értéke. Ha [String::Empty](../../../system/string/empty/) vagy **nullptr** kerül átadásra, egy üres elem jön létre. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)