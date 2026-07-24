---
title: MoveToFollowing()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XPathNavigator zum Element mit dem angegebenen lokalen Namen und dem Namespace-URI in Dokumentreihenfolge.
type: docs
weight: 703
url: /de/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) Methode

Verschiebt den [XPathNavigator](../) zu dem Element mit dem angegebenen lokalen Namen und dem Namespace-URI in Dokumentreihenfolge.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Elements. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Elements. |

### Rückgabewert

**true** wenn der [XPathNavigator](../) erfolgreich verschoben wurde; andernfalls **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) Methode

Verschiebt den [XPathNavigator](../) zu dem Element mit dem angegebenen lokalen Namen und dem Namespace-URI, zum angegebenen Grenzwert, in Dokumentreihenfolge.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Elements. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Elements. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Das [XPathNavigator](../)-Objekt, das an der Elementgrenze positioniert ist und das aktuelle [XPathNavigator](../) beim Suchen des folgenden Elements nicht überschreiten wird. |

### Rückgabewert

**true** wenn der [XPathNavigator](../) erfolgreich verschoben wurde; andernfalls **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) Methode


Verschiebt den [XPathNavigator](../) zum folgenden Element des angegebenen XPathNodeType in Dokumentreihenfolge.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType des Elements. Der XPathNodeType darf nicht [XPathNodeType::Attribute](../../xpathnodetype/) oder [XPathNodeType::Namespace](../../xpathnodetype/) sein. |

### Rückgabewert

**true** wenn der [XPathNavigator](../) erfolgreich verschoben wurde; andernfalls **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) Methode


Verschiebt den [XPathNavigator](../) zum folgenden Element des angegebenen XPathNodeType, zum angegebenen Grenzwert, in Dokumentreihenfolge.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType des Elements. Der XPathNodeType darf nicht [XPathNodeType::Attribute](../../xpathnodetype/) oder [XPathNodeType::Namespace](../../xpathnodetype/) sein. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Das [XPathNavigator](../)-Objekt, das an der Elementgrenze positioniert ist und das aktuelle [XPathNavigator](../) beim Suchen des folgenden Elements nicht überschreiten wird. |

### Rückgabewert

**true** wenn der [XPathNavigator](../) erfolgreich verschoben wurde; andernfalls **false**.

## Siehe auch

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)