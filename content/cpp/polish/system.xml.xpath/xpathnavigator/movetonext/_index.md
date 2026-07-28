---
title: MoveToNext()
second_title: Aspose.Slides dla C++ – referencja API
description: Gdy zostanie przesłonięta w klasie pochodnej, przenosi XPathNavigator do następnego węzła rodzeństwa bieżącego węzła.
type: docs
weight: 586
url: /pl/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metoda


Gdy zostanie przesłonięta w klasie pochodnej, przenosi [XPathNavigator](../) do następnego węzła rodzeństwa bieżącego węzła.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się pomyślnie przeniesieniem do następnego węzła rodzeństwa; w przeciwnym razie **false** jeśli nie ma już więcej rodzeństwa lub jeśli [XPathNavigator](../) jest obecnie ustawiony na węzeł atrybutu. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## XPathNavigator::MoveToNext(String, String) metoda


Przenosi [XPathNavigator](../) do następnego węzła rodzeństwa o podanej nazwie lokalnej i URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa następnego węzła rodzeństwa, do którego ma zostać przeniesiony. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw następnego węzła rodzeństwa, do którego ma zostać przeniesiony. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się pomyślnie przeniesieniem do następnego węzła rodzeństwa; **false** jeśli nie ma już więcej rodzeństwa, lub jeśli [XPathNavigator](../) jest obecnie ustawiony na węzeł atrybutu. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## XPathNavigator::MoveToNext(XPathNodeType) metoda


Przenosi [XPathNavigator](../) do następnego węzła rodzeństwa bieżącego węzła, który pasuje do określonego XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType węzła rodzeństwa, do którego ma zostać przeniesiony. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się pomyślnie przeniesieniem do następnego węzła rodzeństwa; w przeciwnym razie **false** jeśli nie ma już więcej rodzeństwa lub jeśli [XPathNavigator](../) jest obecnie ustawiony na węzeł atrybutu. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## Zobacz także

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)