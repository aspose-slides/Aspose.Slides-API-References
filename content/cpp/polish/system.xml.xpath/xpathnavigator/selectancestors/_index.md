---
title: SelectAncestors()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wybiera wszystkie węzły przodków bieżącego węzła, które mają pasujący XPathNodeType.
type: docs
weight: 846
url: /pl/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metoda


Wybiera wszystkie węzły przodków bieżącego węzła, które mają odpowiadający XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


### Parametry

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType węzłów przodków. |
| matchSelf | **bool** | Aby uwzględnić węzeł kontekstu w wyborze, **true**; w przeciwnym razie **false**. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły. Zwrócone węzły są w odwrotnej kolejności dokumentu.

## XPathNavigator::SelectAncestors(String, String, bool) metoda


Wybiera wszystkie węzły przodków bieżącego węzła, które mają określoną nazwę lokalną i URI przestrzeni nazw.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


### Parametry

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa węzłów przodków. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw węzłów przodków. |
| matchSelf | **bool** | Aby uwzględnić węzeł kontekstu w wyborze, **true**; w przeciwnym razie **false**. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły. Zwrócone węzły są w odwrotnej kolejności dokumentu.

## Zobacz także

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNodeIterator](../../xpathnodeiterator/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)