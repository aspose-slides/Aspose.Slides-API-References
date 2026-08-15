---
title: operator+=()
second_title: Aspose.Slides for C++ API 參考
description: 重設目前物件，使其表示為空值。
type: docs
weight: 235
url: /zh-hant/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) 方法


重設目前物件，使其表示為空值。

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### 返回值

自身的副本

## Nullable::operator+=(const T1\&) 方法


將 [operator+=()](./) 套用於目前物件所表示的值，使用指定的值作為右側引數。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 用作 [operator+=()](./) 之右側值的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 對目前物件所表示的值套用的 [operator+=()](./) 之右側值的常量參考。 |

### 返回值

指向自身的參考

## Nullable::operator+=(const Nullable\<T1\>\&) 方法


將 [operator+=()](./) 套用於目前物件所表示的值，使用指定的 [Nullable](../) 物件所表示的值作為右側引數。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | [Nullable](../) 物件的底層類型，其所表示的值用作 [operator+=()](./) 的右側引數 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 指向 [Nullable](../) 物件的常量參考，其所表示的值用作套用於目前物件所表示的值之 [operator+=()](./) 的右側引數。 |

### 返回值

指向自身的參考

## 另請參閱

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)