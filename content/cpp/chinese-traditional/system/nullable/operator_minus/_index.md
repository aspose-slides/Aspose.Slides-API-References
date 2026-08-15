---
title: operator-()
second_title: Aspose.Slides for C++ API 參考
description: 減去可為 null 且指向 null 的值。
type: docs
weight: 222
url: /zh-hant/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const 方法

減去可為 null 且指向 null 的值。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | Right operand type, should be nullptr_t. |

### 返回值

空的 [Nullable](../) 物件。

## Nullable::operator-(const T1\&) const 方法

減去可為 null 與非 null 的值。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | Right operand type. |

### 引數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| other | const T1\& | 要減去的值。 |

### 返回值

減法結果。

## Nullable::operator-(const Nullable\<T1\>\&) const 方法

減去可為 null 的值。

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | Right operand type. |

### 引數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要減去的值。 |

### 返回值

減法結果。

## 另見

* 類別 [Nullable](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)