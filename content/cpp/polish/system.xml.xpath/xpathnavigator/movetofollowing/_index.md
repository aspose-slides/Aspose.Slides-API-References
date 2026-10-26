---
title: MoveToFollowing()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przenosi XPathNavigator do elementu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw w kolejności dokumentu.
type: docs
weight: 703
url: /pl/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metoda

Przenosi [XPathNavigator](../) do elementu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw w kolejności dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw elementu. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) został przeniesiony pomyślnie; w przeciwnym razie **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metoda

Przenosi [XPathNavigator](../) do elementu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw, do określonej granicy, w kolejności dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw elementu. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) umieszczony na granicy elementu, której bieżący [XPathNavigator](../) nie przekroczy podczas wyszukiwania kolejnego elementu. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) został przeniesiony pomyślnie; w przeciwnym razie **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metoda

Przenosi [XPathNavigator](../) do kolejnego elementu o określonym XPathNodeType w kolejności dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType elementu. XPathNodeType nie może być [XPathNodeType::Attribute](../../xpathnodetype/) ani [XPathNodeType::Namespace](../../xpathnodetype/). |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) został przeniesiony pomyślnie; w przeciwnym razie **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metoda

Przenosi [XPathNavigator](../) do kolejnego elementu o określonym XPathNodeType, do określonej granicy, w kolejności dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType elementu. XPathNodeType nie może być [XPathNodeType::Attribute](../../xpathnodetype/) ani [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) umieszczony na granicy elementu, której bieżący [XPathNavigator](../) nie przekroczy podczas wyszukiwania kolejnego elementu. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) został przeniesiony pomyślnie; w przeciwnym razie **false**.

## Zobacz także

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)