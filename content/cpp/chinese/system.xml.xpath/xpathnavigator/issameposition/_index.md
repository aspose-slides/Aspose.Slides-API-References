---
title: IsSamePosition()
second_title: Aspose.Slides C++ API 参考
description: 当在派生类中被重写时，确定当前 XPathNavigator 是否与指定的 XPathNavigator 处于相同位置。
type: docs
weight: 716
url: /zh/system.xml.xpath/xpathnavigator/issameposition/
---
## XPathNavigator::IsSamePosition(SharedPtr\<XPathNavigator\>) 方法


当在派生类中被重写时，确定当前 [XPathNavigator](../) 是否与指定的 [XPathNavigator](../) 处于相同位置。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::IsSamePosition(SharedPtr<XPathNavigator> other)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 用于与此 [XPathNavigator](../) 比较的 [XPathNavigator](../)。 |

### 返回值

**true** 如果两个 [XPathNavigator](../) 对象位于相同位置；否则 **false**。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)