---
title: PrependChildElement()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový podřízený prvek na začátku seznamu podřízených uzlů aktuálního uzlu pomocí předpony jmenného prostoru, lokálního názvu a URI jmenného prostoru určených zadanou hodnotou.
type: docs
weight: 989
url: /cs/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metoda

Vytvoří nový podřízený prvek na začátku seznamu podřízených uzlů aktuálního uzlu pomocí předpony jmenného prostoru, lokálního názvu a URI jmenného prostoru určených hodnotou.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona jmenného prostoru nového podřízeného prvku (pokud existuje). |
| localName | [String](../../../system/string/) | Lokální název nového podřízeného prvku (pokud existuje). |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru nového podřízeného prvku (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| value | [String](../../../system/string/) | Hodnota nového podřízeného prvku. Pokud je předáno [String::Empty](../../../system/string/empty/) nebo **nullptr**, vytvoří se prázdný prvek. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)