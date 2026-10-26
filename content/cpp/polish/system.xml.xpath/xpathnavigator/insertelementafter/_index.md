---
title: InsertElementAfter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nowy element siostrzany po bieżącym węźle, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw, z określoną wartością.
type: docs
weight: 1028
url: /pl/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) metoda

Tworzy nowy element siostrzany po bieżącym węźle, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw, oraz określonej wartości.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks przestrzeni nazw nowego elementu potomnego (jeśli istnieje). |
| localName | [String](../../../system/string/) | Lokalna nazwa nowego elementu potomnego (jeśli istnieje). |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw nowego elementu potomnego (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |
| value | [String](../../../system/string/) | Wartość nowego elementu potomnego. Jeśli [String::Empty](../../../system/string/empty/) lub **nullptr** zostaną przekazane, tworzony jest pusty element. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)