---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API 参考
description: 选择当前节点的所有具有匹配 XPathNodeType 的祖先节点。
type: docs
weight: 846
url: /zh/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) 方法

选择当前节点的所有具有匹配 XPathNodeType 的祖先节点。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 祖先节点的 XPathNodeType。 |
| matchSelf | **bool** | 在选择中包含上下文节点，**true**；否则为 **false**。 |

### 返回值

一个包含所选节点的 [XPathNodeIterator](../../xpathnodeiterator/)。返回的节点按文档顺序的相反顺序排列。

## XPathNavigator::SelectAncestors(String, String, bool) 方法

选择当前节点的所有具有指定本地名称和命名空间 URI 的祖先节点。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 祖先节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 祖先节点的命名空间 URI。 |
| matchSelf | **bool** | 在选择中包含上下文节点，**true**；否则为 **false**。 |

### 返回值

一个包含所选节点的 [XPathNodeIterator](../../xpathnodeiterator/)。返回的节点按文档顺序的相反顺序排列。

## 另请参阅

* 枚举 [XPathNodeType](../../xpathnodetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNodeIterator](../../xpathnodeiterator/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)