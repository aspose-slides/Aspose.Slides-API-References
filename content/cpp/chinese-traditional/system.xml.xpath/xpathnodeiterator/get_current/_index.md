---
title: get_Current()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，取得此 XPathNodeIterator 的 XPathNavigator 物件，並定位於目前的上下文節點。
type: docs
weight: 1
url: /zh-hant/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() 方法

當在衍生類別中覆寫時，取得此 [XPathNodeIterator](../) 的 [XPathNavigator](../../xpathnavigator/) 物件，並定位於目前的上下文節點。

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### 返回值

一個定位於選取節點集合之上下文節點的 [XPathNavigator](../../xpathnavigator/) 物件。必須呼叫 [XPathNodeIterator::MoveNext](../movenext/) 方法以將 [XPathNodeIterator](../) 移至所選集合中的第一個節點。

## 參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNavigator](../../xpathnavigator/)
* 類別 [XPathNodeIterator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)