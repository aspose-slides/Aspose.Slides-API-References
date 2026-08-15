---
title: operator|=()
second_title: Aspose.Slides C++ API 參考文件
description: 將 operator|=() 套用於目前物件所代表的值，並使用指定的值作為右側參數。
type: docs
weight: 261
url: /zh-hant/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) 方法

將 [operator|=()](./) 套用於目前物件所代表的值，並使用指定的值作為右側參數。

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 用於使 SFINAE 工作的模板參數。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | **bool** | 布林值，用作套用於目前物件所代表的值之 [operator|=()](./) 的右側值。 |

### 傳回值

指向自身的參考。

## 參見

* 類別 [Nullable](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)