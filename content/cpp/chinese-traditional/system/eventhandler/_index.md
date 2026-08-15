---
title: EventHandler
second_title: Aspose.Slides for C++ API 參考
description: "代表一個對事件作出回應並處理的方法。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 3706
url: /zh-hant/system/eventhandler/
---
## EventHandler typedef

代表一個對事件作出回應並處理的方法。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## 參見

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)