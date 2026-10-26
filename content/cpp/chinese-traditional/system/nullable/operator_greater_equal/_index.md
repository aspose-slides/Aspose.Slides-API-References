---
title: operator>=()
second_title: Aspose.Slides for C++ API 參考
description: 永遠返回 false.
type: docs
weight: 183
url: /zh-hant/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const 方法

永遠返回 false。

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### 返回值

永遠 - false

## Nullable::operator>=(const T1\&) const 方法

判斷目前物件所表示的值是否大於或等於指定物件所表示的值，方法是對這些值套用 [operator>=()](./)。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 目前物件所表示的值要與之比較的值的底層型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const T1\& | 與目前物件比較的物件之常量參考 |

### 返回值

如果目前物件所表示的值大於或等於指定物件所表示的值，則為 True；否則為 - false

## Nullable::operator>=(const Nullable\<T1\>\&) const 方法

判斷目前物件所表示的值是否大於或等於指定 [Nullable](../) 物件所表示的值，方法是對這些值套用 [operator>=()](./)。

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 用於比較的 [Nullable](../) 物件的底層型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 與之比較的 [Nullable](../) 物件之常量參考 |

### 返回值

如果目前物件所表示的值大於或等於指定 [Nullable](../) 物件所表示的值，則為 True；否則為 - false

## 另請參閱

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)