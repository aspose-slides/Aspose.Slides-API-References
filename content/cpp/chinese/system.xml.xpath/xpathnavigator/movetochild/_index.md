---
title: MoveToChild()
second_title: Aspose.Slides for C++ API 参考
description: 将 XPathNavigator 移动到具有指定本地名称和命名空间 URI 的子节点。
type: docs
weight: 690
url: /zh/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) 方法

将 [XPathNavigator](../) 移动到具有指定本地名称和命名空间 URI 的子节点。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移动到的子节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要移动到的子节点的命名空间 URI。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到子节点；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## XPathNavigator::MoveToChild(XPathNodeType) 方法

将 [XPathNavigator](../) 移动到指定的 XPathNodeType 的子节点。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要移动到的子节点的 XPathNodeType。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到子节点；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## 另见

* 枚举 [XPathNodeType](../../xpathnodetype/)
* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)