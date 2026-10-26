---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考
description: 判斷目前物件所代表的值是否為非 null。
type: docs
weight: 144
url: /zh-hant/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const 方法


判斷目前物件所代表的值是否為非 null。

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### 返回值

True if the value represented by the current object is not null, otherwise - false

## Nullable::operator!=(const T1\&) const 方法


判斷目前物件所代表的值是否不等於指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### 返回值

True if the value represented by the current object is not equal to the specified value, otherwise - false

## Nullable::operator!=(const Nullable\<T1\>\&) const 方法


判斷目前物件所代表的值是否不等於指定 [Nullable](../) 物件所代表的值。

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### 返回值

True if the value represented by the current object is not equal to the value represented by the specified [Nullable](../) object, otherwise - false

## 另見

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)