---
title: operator==()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前物件所代表的值是否為 null。
type: docs
weight: 118
url: /zh-hant/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method

判斷目前物件所代表的值是否為 null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### 返回值

如果目前物件所代表的值為 null，則為 True，否則為 false

## Nullable::operator==(const T1\&) const method

判斷目前物件所代表的值是否等於指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 用於比較的值的型別 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 要比較的值的常量參考 |

### 返回值

如果目前物件所代表的值等於指定的值，則為 True，否則為 false

## Nullable::operator==(const Nullable\<T1\>\&) const method

判斷目前物件所代表的值是否等於指定 [Nullable](../) 物件所代表的值。

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 用於比較的 [Nullable](../) 物件的底層型別 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 指向要比較的 [Nullable](../) 物件的常量參考 |

### 返回值

如果目前物件所代表的值等於指定 [Nullable](../) 物件所代表的值，則為 True，否則為 false

## 參見

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)