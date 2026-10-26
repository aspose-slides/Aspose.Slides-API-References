---
title: MoveTo()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，將 XPathNavigator 移動到與指定的 XPathNavigator 相同的位置。
type: docs
weight: 664
url: /zh-hant/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) 方法

當在衍生類別中覆寫時，將 [XPathNavigator](../) 移動到與指定的 [XPathNavigator](../) 相同的位置。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 位於您想移動到之節點上的 [XPathNavigator](../)。 |

### 傳回值

**true** 如果 [XPathNavigator](../) 成功移動到與指定的 [XPathNavigator](../) 相同的位置；否則為 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)