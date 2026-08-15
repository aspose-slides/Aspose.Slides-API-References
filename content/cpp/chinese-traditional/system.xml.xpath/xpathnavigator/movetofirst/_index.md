---
title: MoveToFirst()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 XPathNavigator 移動到目前節點的第一個兄弟節點。
type: docs
weight: 612
url: /zh-hant/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() 方法


將 [XPathNavigator](../) 移動到目前節點的第一個兄弟節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### 返回值

**true** 表示 [XPathNavigator](../) 成功移動到目前節點的第一個兄弟節點；**false** 表示沒有第一個兄弟節點，或是 [XPathNavigator](../) 目前位於屬性節點上。若 [XPathNavigator](../) 已經位於第一個兄弟節點，[XPathNavigator](../) 會返回 **true** 並且不會改變其位置。若 [XPathNavigator::MoveToFirst](./) 返回 **false** 因為沒有第一個兄弟節點，或是 [XPathNavigator](../) 目前位於屬性節點，[XPathNavigator](../) 的位置將保持不變。

## 另請參閱

* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)