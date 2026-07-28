---
title: CreateAttribute()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy węzeł atrybutu w bieżącym węźle elementu, używając podanego prefiksu przestrzeni nazw, nazwy lokalnej oraz identyfikatora URI przestrzeni nazw, z określoną wartością.
type: docs
weight: 1041
url: /pl/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metoda

Tworzy węzeł atrybutu w bieżącym węźle elementu, używając podanego prefiksu przestrzeni nazw, nazwy lokalnej oraz identyfikatora URI przestrzeni nazw, wraz z określoną wartością.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks przestrzeni nazw nowego węzła atrybutu (jeśli istnieje). |
| localName | [String](../../../system/string/) | Lokalna nazwa nowego węzła atrybutu, która nie może [String::Empty](../../../system/string/empty/) lub **nullptr**. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw dla nowego węzła atrybutu (jeśli istnieje). |
| value | [String](../../../system/string/) | Wartość nowego węzła atrybutu. Jeśli [String::Empty](../../../system/string/empty/) lub **nullptr** zostaną przekazane, tworzony jest pusty węzeł atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)