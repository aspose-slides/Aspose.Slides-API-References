---
title: Nullable()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個表示 null 值的實例。
type: docs
weight: 1
url: /zh-hant/system/nullable/nullable/
---
## Nullable::Nullable() 建構子

建構一個表示 null 值的實例。

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) 建構子

建構一個表示 null 的實例。

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) 建構子

建構一個 [Nullable](../) 類別的實例，該實例表示指定的值，若有需要則會轉換為底層類型 T 的值。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 指定值的型別 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T1\& | 要由新建的 [Nullable](../) 物件所表示的值的常量參考 |

## Nullable::Nullable(const Nullable\<T1\>\&) 建構子

建構一個實例，該實例表示由指定的 [Nullable](../) 物件所代表的值。指定的可為 null 物件可能代表與建構實例的底層類型不同的型別，此時會將該值轉換為型別 T 的值。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 指定的 [Nullable](../) 物件所代表的值的型別 |

## 參見

* 類別 [Nullable](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)