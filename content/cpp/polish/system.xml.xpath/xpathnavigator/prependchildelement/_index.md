---
title: PrependChildElement()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy nowy element potomny na początku listy węzłów potomnych bieżącego węzła, używając prefiksu przestrzeni nazw, nazwy lokalnej oraz identyfikatora URI przestrzeni nazw określonych wraz z podaną wartością.
type: docs
weight: 989
url: /pl/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metoda

Tworzy nowy element potomny na początku listy węzłów potomnych bieżącego węzła, używając prefiksu przestrzeni nazw, nazwy lokalnej oraz identyfikatora URI przestrzeni nazw określonych wraz z podaną wartością.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks przestrzeni nazw nowego elementu potomnego (jeśli istnieje). |
| localName | [String](../../../system/string/) | Nazwa lokalna nowego elementu potomnego (jeśli istnieje). |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw nowego elementu potomnego (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |
| value | [String](../../../system/string/) | Wartość nowego elementu potomnego. Jeśli [String::Empty](../../../system/string/empty/) lub **nullptr** zostaną przekazane, tworzony jest pusty element. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)