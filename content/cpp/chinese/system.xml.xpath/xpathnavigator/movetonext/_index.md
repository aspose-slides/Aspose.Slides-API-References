---
title: MoveToNext()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被重写时，将 XPathNavigator 移动到当前节点的下一个兄弟节点。
type: docs
weight: 586
url: /zh/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() 方法

When overridden in a derived class, moves the [XPathNavigator](../) to the next sibling node of the current node.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### 返回值

**true** 若 [XPathNavigator](../) 成功移动到下一个兄弟节点；否则 **false** 表示没有更多兄弟节点或 [XPathNavigator](../) 当前位于属性节点。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## XPathNavigator::MoveToNext(String, String) 方法

Moves the [XPathNavigator](../) to the next sibling node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移动到的下一个兄弟节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要移动到的下一个兄弟节点的命名空间 URI。 |

### 返回值

**true** 若 [XPathNavigator](../) 成功移动到下一个兄弟节点；**false** 表示没有更多兄弟节点，或者 [XPathNavigator](../) 当前位于属性节点。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## XPathNavigator::MoveToNext(XPathNodeType) 方法

Moves the [XPathNavigator](../) to the next sibling node of the current node that matches the XPathNodeType specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要移动到的兄弟节点的 XPathNodeType。 |

### 返回值

**true** 若 [XPathNavigator](../) 成功移动到下一个兄弟节点；否则 **false** 表示没有更多兄弟节点，或 [XPathNavigator](../) 当前位于属性节点。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## 另见

* 枚举 [XPathNodeType](../../xpathnodetype/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)