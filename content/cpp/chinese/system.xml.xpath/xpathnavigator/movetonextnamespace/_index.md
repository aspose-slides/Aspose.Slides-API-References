---
title: MoveToNextNamespace()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中重写时，将 XPathNavigator 移动到与指定的 XPathNamespaceScope 匹配的下一个命名空间节点。
type: docs
weight: 573
url: /zh/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) 方法


When overridden in a derived class, moves the [XPathNavigator](../) to the next namespace node matching the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 描述命名空间范围的 XPathNamespaceScope 值。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到下一个命名空间节点；否则为 **false**。如果为 **false**，[XPathNavigator](../) 的位置保持不变。

## XPathNavigator::MoveToNextNamespace() 方法


Moves the [XPathNavigator](../) to the next namespace node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到下一个命名空间节点；否则为 **false**。如果为 **false**，[XPathNavigator](../) 的位置保持不变。

## 另见

* 枚举 [XPathNamespaceScope](../../xpathnamespacescope/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)