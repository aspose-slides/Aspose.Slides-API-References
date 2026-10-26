---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，将 XPathNavigator 移动到匹配指定 XPathNamespaceScope 的第一个命名空间节点。
type: docs
weight: 560
url: /zh/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) 方法

当在派生类中重写时，将 [XPathNavigator](../) 移动到匹配指定 XPathNamespaceScope 的第一个命名空间节点。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 描述命名空间范围的 XPathNamespaceScope 值。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到第一个命名空间节点；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## XPathNavigator::MoveToFirstNamespace() 方法

将 [XPathNavigator](../) 移动到当前节点的第一个命名空间节点。

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到第一个命名空间节点；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## 另请参见

* 枚举 [XPathNamespaceScope](../../xpathnamespacescope/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)