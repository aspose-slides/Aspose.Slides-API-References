---
title: operator<=()
second_title: Aspose.Slides C++ API 參考文件
description: 總是返回 false。
type: docs
weight: 196
url: /zh-hant/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const 方法

始終返回 false。

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const 方法

判斷目前物件所代表的值是否小於或等於指定的值，方法是對這些值套用 [operator<=()](./)。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 要比較的值的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const T1\& | 要比較的值的常量參考 |

### 傳回值

若目前物件所代表的值小於或等於指定的值，則返回 true，否則返回 false

## Nullable::operator<=(const Nullable\<T1\>\&) const 方法

判斷目前物件所代表的值是否小於或等於指定 [Nullable](../) 物件所代表的值，方法是對這些值套用 [operator<=()](./)。

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 要比較的 [Nullable](../) 物件的底層型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要比較的 [Nullable](../) 物件的常量參考 |

### 傳回值

若目前物件所代表的值小於或等於指定 [Nullable](../) 物件所代表的值，則返回 true，否則返回 false

## 另請參閱

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)