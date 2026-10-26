---
title: operator+()
second_title: Aspose.Slides for C++ API 參考
description: 傳回 Nullable<T> 類別的預設構造實例。
type: docs
weight: 209
url: /zh-hant/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const 方法

傳回 Nullable<T> 類別的預設構造實例。

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const 方法

對可空值和非可空值進行加總。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 右操作元型別。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | const T1\& | 要加入的值。 |

### 回傳值

加總結果。

## Nullable::operator+(const Nullable\<T1\>\&) const 方法

將可空值相加。

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 右操作元型別。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要加入的值。 |

### 回傳值

加總結果。

## 另請參閱

* 類別 [Nullable](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)