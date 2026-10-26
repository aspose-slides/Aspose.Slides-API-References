---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API 參考文件
description: "Object::ReferenceEquals 於字串與 nullptr 情況的特化。"
type: docs
weight: 261
url: /zh-hant/system/object/referenceequals/
---
## Object::ReferenceEquals(String const&, std::nullptr_t) 方法


針對字串和 nullptr 情況的 [Object::ReferenceEquals](./) 特化。

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) 用於與 nullptr 比較。 |

### 返回值

若字串為 null，則返回 true，否則返回 false。

## Object::ReferenceEquals(String const&, String const&) 方法


針對字串情況的 [Object::ReferenceEquals](./) 特化。

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | 第一個字串用於比較。 |
| str2 | [String](../../string/) const\& | 第二個字串用於比較。 |

### 返回值

若字串相符則返回 true，否則返回 false。

## Object::ReferenceEquals(ptr const&, ptr const&) 方法


以參考方式比較物件。

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | 第一個指標用於比較。 |
| objB | [ptr](../ptr/) const\& | 第二個指標用於比較。 |

### 返回值

若指標相符則返回 true，否則返回 false。

## Object::ReferenceEquals(T const&, T const&) 方法


以參考方式比較物件。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 用於比較的物件型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | 第一個物件用於比較。 |
| objB | T const\& | 第二個物件用於比較。 |

### 返回值

若物件位址相符則返回 true，否則返回 false。

## Object::ReferenceEquals(T const&, std::nullptr_t) 方法


以參考方式比較值型別物件與 nullptr。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 用於比較的物件型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | 第一個物件用於比較。 |

### 返回值

始終返回 false，因為值型別無法為 nullptr。

## 另見

* 型別別名 [ptr](../ptr/)
* 類別 [String](../../string/)
* 類別 [Object](../)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)