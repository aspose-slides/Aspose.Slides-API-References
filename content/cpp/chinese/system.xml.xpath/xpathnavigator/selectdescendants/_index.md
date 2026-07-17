---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API 参考
description: 选择当前节点的所有后代节点，这些节点的 XPathNodeType 与之匹配。
type: docs
weight: 859
url: /zh/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) 方法

选择当前节点的所有后代节点，这些节点的 XPathNodeType 与指定的匹配。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 后代节点的 XPathNodeType。 |
| matchSelf | **bool** | **true** 若在选择中包含上下文节点；否则 **false**。 |

### 返回值

一个包含所选节点的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::SelectDescendants(String, String, bool) 方法

选择当前节点的所有后代节点，这些节点具有指定的本地名称和命名空间 URI。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 后代节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 后代节点的命名空间 URI。 |
| matchSelf | **bool** | **true** 若在选择中包含上下文节点；否则 **false**。 |

### 返回值

一个包含所选节点的 [XPathNodeIterator](../../xpathnodeiterator/)。

## 另请参见

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNodeIterator](../../xpathnodeiterator/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)