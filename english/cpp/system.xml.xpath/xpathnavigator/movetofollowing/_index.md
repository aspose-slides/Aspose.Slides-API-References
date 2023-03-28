---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API Reference
description: Moves the XPathNavigator to the element with the local name and namespace URI specified in document order.
type: docs
weight: 703
url: /cpp/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing([String](../../../system/string/), [String](../../../system/string/)) method


Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::MoveToFollowing([String](../../../system/string/), [String](../../../system/string/), [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\>) method


Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### Return Value

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::MoveToFollowing([XPathNodeType](../../xpathnodetype/)) method


Moves the [XPathNavigator](../) to the following element of the XPathNodeType specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the element. The XPathNodeType cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |

### Return Value

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::MoveToFollowing([XPathNodeType](../../xpathnodetype/), [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\>) method


Moves the [XPathNavigator](../) to the following element of the XPathNodeType specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the element. The XPathNodeType cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### Return Value

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
