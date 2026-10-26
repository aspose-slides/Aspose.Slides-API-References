---
title: operator-=()
second_title: Aspose.Slides for C++ API 參考
description: 傳回表示空值的 Nullable 類別實例。
type: docs
weight: 248
url: /zh-hant/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) 方法

傳回 [Nullable](../) 類別的實例，此實例表示空值。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) 方法

對目前物件所表示的值套用 [operator-=()](./)，使用指定的值作為右側參數。

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 作為 [operator-=()](./) 之右側值所使用的值的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | const T1\& | 對目前物件所表示的值套用的 [operator-=()](./)，其右側值使用的值之常量參照。 |

### 傳回值

對自身的參考

## Nullable::operator-=(const Nullable\<T1\>\&) 方法

對目前物件所表示的值套用 [operator-=()](./)，使用指定的 [Nullable](../) 物件所表示的值作為右側參數。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 作為 [operator-=()](./) 之右側參數所使用的 [Nullable](../) 物件所表示之值的底層型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 對目前物件所表示的值套用的 [operator-=()](./)，其右側參數使用的值為 [Nullable](../) 物件所表示之值之常量參照。 |

### 傳回值

對自身的參考

## 另見

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)