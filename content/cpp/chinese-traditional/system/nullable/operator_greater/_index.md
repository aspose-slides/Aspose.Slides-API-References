---
title: operator>()
second_title: Aspose.Slides for C++ API 參考
description: 始終傳回 false。
type: docs
weight: 157
url: /zh-hant/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const 方法


始終傳回 false。

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const 方法


判斷目前物件所代表的值是否透過套用 [operator>()](./) 於這些值而大於指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 要比較的值的型別 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const T1\& | 要比較的值的常數參照 |

### 返回值

若目前物件所代表的值大於指定的值則傳回 true，否則傳回 false

## Nullable::operator>(const Nullable\<T1\>\&) const 方法


判斷目前物件所代表的值是否透過套用 [operator>()](./) 於這些值而大於指定 [Nullable](../) 物件所代表的值。

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 要與之比較的 [Nullable](../) 物件的底層型別 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要比較的 [Nullable](../) 物件的常數參照 |

### 返回值

若目前物件所代表的值大於指定 [Nullable](../) 物件所代表的值則傳回 true，否則傳回 false

## 另請參閱

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)