---
title: CreateAttribute()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří uzel atributu na aktuálním uzlu elementu pomocí předpony jmenného prostoru, lokálního názvu a URI jmenného prostoru určených s určenou hodnotou.
type: docs
weight: 1041
url: /cs/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metoda

Vytvoří uzel atributu na aktuálním uzlu elementu pomocí předpony jmenného prostoru, lokálního názvu a URI jmenného prostoru zadaných s určenou hodnotou.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona jmenného prostoru nového uzlu atributu (pokud existuje). |
| localName | [String](../../../system/string/) | Lokální název nového uzlu atributu, který nesmí [String::Empty](../../../system/string/empty/) nebo **nullptr**. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru pro nový uzel atributu (pokud existuje). |
| value | [String](../../../system/string/) | Hodnota nového uzlu atributu. Pokud je předáno [String::Empty](../../../system/string/empty/) nebo **nullptr**, vytvoří se prázdný uzel atributu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)