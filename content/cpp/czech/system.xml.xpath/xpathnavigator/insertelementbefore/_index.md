---
title: InsertElementBefore()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří nový sourozenecký element před aktuálním uzlem pomocí zadané předpony jmenného prostoru, místního názvu a URI jmenného prostoru, s určenou hodnotou.
type: docs
weight: 1015
url: /cs/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) metoda


Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona jmenného prostoru nového podřízeného elementu (pokud existuje). |
| localName | [String](../../../system/string/) | Místní název nového podřízeného elementu (pokud existuje). |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru nového podřízeného elementu (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| value | [String](../../../system/string/) | Hodnota nového podřízeného elementu. Pokud je předáno [String::Empty](../../../system/string/empty/) nebo **nullptr**, je vytvořen prázdný element. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)