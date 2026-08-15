---
title: operator&=()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的值作為右側參數，將 operator&=() 套用於目前物件所代表的值。
type: docs
weight: 274
url: /zh-hant/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) 方法

將 [operator&=()](./) 應用於目前物件所代表的值，使用指定的值作為右側參數。

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 用於使 SFINAE 起作用的範本參數。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | **bool** | 布林值，用作套用於目前物件所代表的值之 [operator&=()](./) 的右側值。 |

### 傳回值

返回對自身的參考。

## 參見

* 類別 [Nullable](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)