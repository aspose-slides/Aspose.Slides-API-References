---
title: operator+()
second_title: Aspose.Slides for C++ API 參考文件
description: 字串串接運算子。
type: docs
weight: 274
url: /zh-hant/system/string/operator_plus/
---
## String::operator+(const String\&) const 方法


[String](../) 串接運算子。

```cpp
String System::String::operator+(const String &str) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 以加入至目前字串的結尾。 |

### 傳回值

串接後的字串。

## String::operator+(const T\&) const 方法


[String](../) 串接字串常量或字元字串指標。

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 字串常量或字元字串指標形式之一。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arg | const T\& | 要與目前字串串接的實體。 |

### 傳回值

串接後的字串。

## String::operator+(char_t) const 方法


將字元加入字串的結尾。

```cpp
String System::String::operator+(char_t x) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | char_t | 要加入的字元。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(int) const 方法


將整數值的字串表示加入字串的結尾。

```cpp
String System::String::operator+(int i) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| i | int | 要轉換為字串並加入的整數值。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(uint32_t) const 方法


將無號整數值的字串表示加入字串的結尾。

```cpp
String System::String::operator+(uint32_t i) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| i | **uint32_t** | 要轉換為字串並加入的值。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(double) const 方法


將浮點數值的字串表示加入字串的結尾。

```cpp
String System::String::operator+(double d) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| d | **double** | 要轉換為字串並加入的值。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(int64_t) const 方法


將整數值的字串表示加入字串的結尾。

```cpp
String System::String::operator+(int64_t v) const
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| v | **int64_t** | 要轉換為字串並加入的值。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(const T\&) const 方法


將參考型別物件的字串表示加入字串的結尾。

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 指標型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) 使用 [ToString()](../tostring/) 呼叫轉換為字串並加入目前字串。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(const T\&) const 方法


將值型別物件的字串表示加入字串的結尾。

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值型別，以呼叫 [ToString()](../tostring/)。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) 使用 [ToString()](../tostring/) 呼叫轉換為字串並加入目前字串。 |

### 傳回值

[String](../) 串接結果。

## String::operator+(T) const 方法


將布林值的字串表示加入字串的結尾。

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 與字串串接的值型別。必須為 bool |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) 值轉換為字串並加入。 |

### 傳回值

[String](../) 串接結果。

## 另請參閱

* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)