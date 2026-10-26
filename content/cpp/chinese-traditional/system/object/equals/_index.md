---
title: Equals()
second_title: Aspose.Slides for C++ API 參考
description: 使用 C# Object.Equals 語意比較物件。
type: docs
weight: 157
url: /zh-hant/system/object/equals/
---
## Object::Equals(ptr) 方法


使用 C# [Object.Equals](./) 語意比較物件。

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) 用於與目前物件比較。 |

### 傳回值

True if objects are considered equal and false otherwise.

## Object::Equals(T1 const\&, T2 const\&) 方法


以 C# 風格比較參考型別物件。

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個要比較的物件型別。 |
| T2 | 第二個要比較的物件型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| objA | T1 const\& | 第一個要比較的物件。 |
| objB | T2 const\& | 第二個要比較的物件。 |

### 傳回值

True if objects match either by reference or semantically (by [Object.Equals](./)-alike comparison), false otherwise.

## Object::Equals(T1 const\&, T2 const\&) 方法


以 C# 風格比較值型別物件。

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個要比較的物件型別。 |
| T2 | 第二個要比較的物件型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| objA | T1 const\& | 第一個要比較的物件。 |
| objB | T2 const\& | 第二個要比較的物件。 |

### 傳回值

True if objects are considered equal by equality operator available, false otherwise.

## Object::Equals(float const\&, float const\&) 方法


模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| objA | **float** const\& | 左側浮點值。 |
| objB | **float** const\& | 右側浮點值。 |

### 傳回值

True if **objA** and **objB** are both NaN or equal, false otherwise.

## Object::Equals(double const\&, double const\&) 方法


模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| objA | **double** const\& | 左側浮點值。 |
| objB | **double** const\& | 右側浮點值。 |

### 傳回值

True if **objA** and **objB** are both NaN or equal, false otherwise.

## 另請參閱

* 型別定義 [ptr](../ptr/)
* 類別 [Object](../)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)