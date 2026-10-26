---
title: AppendChildElement()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový podřízený elementový uzel na konci seznamu podřízených uzlů aktuálního uzlu pomocí zadaného prefixu jmenného prostoru, místního názvu a URI jmenného prostoru spolu se zadanou hodnotou.
type: docs
weight: 1002
url: /cs/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metoda

Vytvoří nový podřízený elementový uzel na konci seznamu podřízených uzlů aktuálního uzlu pomocí zadaného prefixu jmenného prostoru, místního názvu a URI jmenného prostoru spolu se zadanou hodnotou.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefix jmenného prostoru nového podřízeného elementu (pokud existuje). |
| localName | [String](../../../system/string/) | Místní název nového podřízeného elementu (pokud existuje). |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru nového podřízeného elementu (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| value | [String](../../../system/string/) | Hodnota nového podřízeného elementu. Pokud je předáno [String::Empty](../../../system/string/empty/) nebo **nullptr**, je vytvořen prázdný element. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)