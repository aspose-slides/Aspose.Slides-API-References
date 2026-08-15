---
title: get_NewValue()
second_title: Aspose.Slides for C++ API 參考手冊
description: 傳回節點的新值。
type: docs
weight: 66
url: /zh-hant/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() 方法


傳回節點的新值。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### 回傳值

節點的新值。若節點既不是屬性也不是文字節點，或該節點正被移除，此方法會傳回 **nullptr**。如果在 **XmlDocument::NodeChanging** 事件中呼叫，**get_NewValue** 會在變更成功時傳回節點的值。如果在 **XmlDocument::NodeChanged** 事件中呼叫，**get_NewValue** 會傳回節點當前的值。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeChangedEventArgs](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)