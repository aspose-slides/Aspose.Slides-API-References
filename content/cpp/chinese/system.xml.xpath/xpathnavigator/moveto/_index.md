---
title: MoveTo()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被覆盖时，将 XPathNavigator 移动到指定的 XPathNavigator 的相同位置。
type: docs
weight: 664
url: /zh/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) 方法

当在派生类中被覆盖时，将 [XPathNavigator](../) 移动到指定的 [XPathNavigator](../) 的相同位置。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 定位在您想要移动到的节点上的 [XPathNavigator](../)。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到指定的 [XPathNavigator](../) 的相同位置；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)