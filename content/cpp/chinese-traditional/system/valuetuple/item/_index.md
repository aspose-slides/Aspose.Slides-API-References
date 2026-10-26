---
title: Item()
second_title: Aspose.Slides for C++ API 參考
description: 取得 ValueTuple 物件元件之值的參考。
type: docs
weight: 14
url: /zh-hant/system/valuetuple/item/
---
## ValueTuple::Item() 方法

取得 [ValueTuple](../) 物件元件的值的參考。

```cpp
template<std::size_t> std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Index | 類別應返回的項目編號。 |

## ValueTuple::Item() const 方法

取得 [ValueTuple](../) 物件元件的值。

```cpp
template<std::size_t> const std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item() const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Index | 類別應返回的項目編號。 |

## 參見

* 類別 [Index](../../index/)
* 類別 [ValueTuple](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)