---
title: IsSamePosition()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，決定當前的 XPathNavigator 是否與指定的 XPathNavigator 位於相同位置。
type: docs
weight: 716
url: /zh-hant/system.xml.xpath/xpathnavigator/issameposition/
---
## XPathNavigator::IsSamePosition(SharedPtr\<XPathNavigator\>) 方法

當在衍生類別中被覆寫時，決定目前的 [XPathNavigator](../) 是否與指定的 [XPathNavigator](../) 位於相同位置。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::IsSamePosition(SharedPtr<XPathNavigator> other)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 要與此 [XPathNavigator](../) 比較的 [XPathNavigator](../)。 |

### 返回值

**true** 如果兩個 [XPathNavigator](../) 物件具有相同的位置；否則 **false**。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)