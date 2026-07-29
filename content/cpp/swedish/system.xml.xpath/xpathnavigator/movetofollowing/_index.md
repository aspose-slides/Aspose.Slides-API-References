---
title: MoveToFollowing()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar XPathNavigator till elementet med det lokala namnet och namnrymdens URI som anges i dokumentordning.
type: docs
weight: 703
url: /sv/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metod


Flyttar [XPathNavigator](../) till elementet med det lokala namnet och namnrymds-URI som anges i dokumentordning.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmets URI för elementet. |

### Returvärde

**true** om [XPathNavigator](../) flyttades framgångsrikt; annars **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metod


Flyttar [XPathNavigator](../) till elementet med det lokala namnet och namnrymds-URI som anges, till den angivna gränsen, i dokumentordning.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmets URI för elementet. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objektet [XPathNavigator](../) som är placerat på elementgränsen och som den aktuella [XPathNavigator](../) inte kommer att passera medan den söker efter följande element. |

### Returvärde

**true** om [XPathNavigator](../) flyttades framgångsrikt; annars **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metod


Flyttar [XPathNavigator](../) till följande element av den angivna XPathNodeType i dokumentordning.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för elementet. XPathNodeType kan inte vara [XPathNodeType::Attribute](../../xpathnodetype/) eller [XPathNodeType::Namespace](../../xpathnodetype/). |

### Returvärde

**true** om [XPathNavigator](../) flyttades framgångsrikt; annars **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metod


Flyttar [XPathNavigator](../) till följande element av den angivna XPathNodeType, till den angivna gränsen, i dokumentordning.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för elementet. XPathNodeType kan inte vara [XPathNodeType::Attribute](../../xpathnodetype/) eller [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objektet [XPathNavigator](../) som är placerat på elementgränsen och som den aktuella [XPathNavigator](../) inte kommer att passera medan den söker efter följande element. |

### Returvärde

**true** om [XPathNavigator](../) flyttades framgångsrikt; annars **false**.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)