---
title: get_Current()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被重写时，获取此 XPathNodeIterator 的 XPathNavigator 对象，该对象定位在当前上下文节点上。
type: docs
weight: 1
url: /zh/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() 方法


当在派生类中被重写时，获取此 [XPathNodeIterator](../) 的 [XPathNavigator](../../xpathnavigator/) 对象，该对象定位在当前上下文节点上。

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### 返回值

一个定位在选取节点集合的上下文节点上的 [XPathNavigator](../../xpathnavigator/) 对象。必须调用 [XPathNodeIterator::MoveNext](../movenext/) 方法将 [XPathNodeIterator](../) 移动到所选集合中的第一个节点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNavigator](../../xpathnavigator/)
* 类 [XPathNodeIterator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)