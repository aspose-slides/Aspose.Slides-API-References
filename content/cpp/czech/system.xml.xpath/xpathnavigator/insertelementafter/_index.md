---
title: InsertElementAfter()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří nový sourozenecký prvek za aktuálním uzlem pomocí zadané předpony jmenného prostoru, místního názvu a URI jmenného prostoru, s určenou hodnotou.
type: docs
weight: 1028
url: /cs/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) method

Vytvoří nový sourozenecký prvek za aktuálním uzlem pomocí zadaného předpony jmenného prostoru, místního názvu a URI jmenného prostoru, s určenou hodnotou.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona jmenného prostoru nového podřízeného prvku (pokud je). |
| localName | [String](../../../system/string/) | Místní název nového podřízeného prvku (pokud je). |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru nového podřízeného prvku (pokud je). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| value | [String](../../../system/string/) | Hodnota nového podřízeného prvku. Pokud jsou předány [String::Empty](../../../system/string/empty/) nebo **nullptr**, vytvoří se prázdný prvek. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)