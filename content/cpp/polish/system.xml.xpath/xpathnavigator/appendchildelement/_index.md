---
title: AppendChildElement()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy nowy węzeł elementu potomnego na końcu listy węzłów potomnych bieżącego węzła, używając podanego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw oraz określonej wartości.
type: docs
weight: 1002
url: /pl/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metoda


Tworzy nowy węzeł elementu potomnego na końcu listy węzłów potomnych bieżącego węzła, używając podanego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw oraz określonej wartości.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks przestrzeni nazw nowego węzła elementu potomnego (jeśli istnieje). |
| localName | [String](../../../system/string/) | Lokalna nazwa nowego węzła elementu potomnego (jeśli istnieje). |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw nowego węzła elementu potomnego (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |
| value | [String](../../../system/string/) | Wartość nowego węzła elementu potomnego. Jeśli zostanie przekazany [String::Empty](../../../system/string/empty/) lub **nullptr**, tworzony jest pusty element. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)