---
title: dynamic_pointer_cast()
second_title: Aspose.Slides C++ API 參考
description: 使用 dynamic_cast 轉換智慧指標。
type: docs
weight: 2926
url: /zh-hant/system/dynamic_pointer_cast/
---
## System::dynamic_pointer_cast(SmartPtr\<X\> const\&) 函式

使用 dynamic_cast 轉換智慧指標。

```cpp
template<class Y,class X> SmartPtr<Y> System::dynamic_pointer_cast(SmartPtr<X> const &x)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| X | 來源指標所指的類型。 |
| Y | 目標指標所指的類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 來源指標。 |

### 返回值

轉型後的指標。

## 參見

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)