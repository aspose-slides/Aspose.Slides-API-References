---
title: ValueType
second_title: Aspose.Slides 用於 C++ API 參考
description: "指向陣列的儲存類型。僅在 T 為 System::Array 的特化時才有意義。"
type: docs
weight: 508
url: /zh-hant/system/smartptr/valuetype/
---
## ValueType typedef

指向陣列的儲存類型。只有在 T 為 [System::Array](../../array/) 的特化時才有意義。

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## 參見

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)