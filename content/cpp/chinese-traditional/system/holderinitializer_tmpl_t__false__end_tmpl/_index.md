---
title: HolderInitializer< T, false >
second_title: Aspose.Slides for C++ API 參考
description: HolderInitializer 特化針對 T 為值類型的情況。使用情境允許返回對臨時物件的參考，因為已保證實例會被呼叫者複製。因此，此特化僅作為存根使用，什麼也不做。
type: docs
weight: 1652
url: /zh-hant/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) 針對 T 為值型別的情況的特化。使用情境允許返回對臨時物件的參考，因為已保證該實例會被呼叫端複製。因此，此特化僅用作存根，什麼也不做。

```cpp
template<typename T>class HolderInitializer< T, false >
```

## 方法

| 方法 | 說明 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)