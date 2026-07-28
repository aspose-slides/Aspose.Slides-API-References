---
title: MoveToChild()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Przenosi XPathNavigator do węzła podrzędnego o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.
type: docs
weight: 690
url: /pl/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metoda


Przenosi [XPathNavigator](../) do węzła podrzędnego o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa węzła podrzędnego, do którego ma nastąpić przejście. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw węzła podrzędnego, do którego ma nastąpić przejście. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się sukcesem przenoszenia do węzła podrzędnego; w przeciwnym razie **false**. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## XPathNavigator::MoveToChild(XPathNodeType) metoda


Przenosi [XPathNavigator](../) do węzła podrzędnego określonego typu XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType węzła podrzędnego, do którego ma nastąpić przejście. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się sukcesem przenoszenia do węzła podrzędnego; w przeciwnym razie **false**. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## Zobacz także

* Wyliczenie [XPathNodeType](../../xpathnodetype/)
* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)