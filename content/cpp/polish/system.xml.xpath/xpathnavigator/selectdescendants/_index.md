---
title: SelectDescendants()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wybiera wszystkie potomne węzły bieżącego węzła, które mają pasujący XPathNodeType.
type: docs
weight: 859
url: /pl/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metoda

Wybiera wszystkie potomne węzły bieżącego węzła, które mają pasujący XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType potomnych węzłów. |
| matchSelf | **bool** | **true** aby uwzględnić węzeł kontekstowy w wyborze; w przeciwnym razie **false**. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły.

## XPathNavigator::SelectDescendants(String, String, bool) metoda

Wybiera wszystkie potomne węzły bieżącego węzła o określonej lokalnej nazwie i URI przestrzeni nazw.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa potomnych węzłów. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw potomnych węzłów. |
| matchSelf | **bool** | **true** aby uwzględnić węzeł kontekstowy w wyborze; w przeciwnym razie **false**. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły.

## Zobacz także

* Wyliczenie [XPathNodeType](../../xpathnodetype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNodeIterator](../../xpathnodeiterator/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)