---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API参考
description: 将 XPathNavigator 移动到文档顺序中具有指定本地名称和命名空间 URI 的元素。
type: docs
weight: 703
url: /zh/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) 方法


将 [XPathNavigator](../) 移动到文档顺序中指定本地名称和命名空间 URI 的元素。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) 方法


将 [XPathNavigator](../) 移动到文档顺序中指定本地名称和命名空间 URI 的元素，直到指定的边界。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 位于元素边界的 [XPathNavigator](../) 对象，当前的 [XPathNavigator](../) 在搜索后续元素时不会越过该边界。 |

### 返回值

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) 方法


将 [XPathNavigator](../) 移动到文档顺序中指定 XPathNodeType 的后续元素。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 元素的 XPathNodeType。XPathNodeType 不能是 [XPathNodeType::Attribute](../../xpathnodetype/) 或 [XPathNodeType::Namespace](../../xpathnodetype/)。 |

### 返回值

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) 方法


将 [XPathNavigator](../) 移动到文档顺序中指定 XPathNodeType 的后续元素，直到指定的边界。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 元素的 XPathNodeType。XPathNodeType 不能是 [XPathNodeType::Attribute](../../xpathnodetype/) 或 [XPathNodeType::Namespace](../../xpathnodetype/)。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 位于元素边界的 [XPathNavigator](../) 对象，当前的 [XPathNavigator](../) 在搜索后续元素时不会越过该边界。 |

### 返回值

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## 参见

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)