---
title: get_OldValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回節點的原始值。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() 方法


傳回節點的原始值。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### 傳回值

節點的原始值。此方法會傳回 **nullptr** 如果該節點既不是屬性也不是文字節點，或該節點正被插入。 如果在 **XmlDocument::NodeChanging** 事件中呼叫，**get_OldValue** 會傳回若變更成功將被取代的節點目前值。 如果在 **XmlDocument::NodeChanged** 事件中呼叫，**get_OldValue** 會傳回變更前的節點值。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeChangedEventArgs](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)