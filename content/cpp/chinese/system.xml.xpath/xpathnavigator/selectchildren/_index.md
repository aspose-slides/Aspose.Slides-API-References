---
title: SelectChildren()
second_title: Aspose.Slides C++ API 参考
description: 选择当前节点的所有子节点，这些子节点的 XPathNodeType 与之匹配。
type: docs
weight: 833
url: /zh/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) 方法


选择当前节点的所有子节点，这些子节点的 XPathNodeType 与之匹配。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 子节点的 XPathNodeType。 |

### 返回值

一个 [XPathNodeIterator](../../xpathnodeiterator/)，其中包含所选节点。

## XPathNavigator::SelectChildren(String, String) 方法


选择当前节点的所有子节点，这些子节点具有指定的本地名称和命名空间 URI。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 子节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 子节点的命名空间 URI。 |

### 返回值

一个 [XPathNodeIterator](../../xpathnodeiterator/)，其中包含所选节点。

## 另请参见

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNodeIterator](../../xpathnodeiterator/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)