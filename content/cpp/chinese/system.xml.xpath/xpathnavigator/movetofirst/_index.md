---
title: MoveToFirst()
second_title: Aspose.Slides for C++ API 参考
description: 将 XPathNavigator 移动到当前节点的第一个兄弟节点。
type: docs
weight: 612
url: /zh/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() 方法


将 [XPathNavigator](../) 移动到当前节点的第一个兄弟节点。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到当前节点的第一个兄弟节点；**false** 如果没有第一个兄弟节点，或 [XPathNavigator](../) 当前位于属性节点上。 如果 [XPathNavigator](../) 已经位于第一个兄弟节点，[XPathNavigator](../) 将返回 **true** 并且不会移动其位置。 如果 [XPathNavigator::MoveToFirst](./) 返回 **false** 因为没有第一个兄弟节点，或 [XPathNavigator](../) 当前位于属性上，[XPathNavigator](../) 的位置保持不变。

## 另请参阅

* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)