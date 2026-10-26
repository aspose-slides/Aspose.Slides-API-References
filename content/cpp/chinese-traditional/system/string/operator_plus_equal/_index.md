---
title: operator+=()
second_title: Aspose.Slides for C++ API 參考
description: 串接賦值運算子。
type: docs
weight: 287
url: /zh-hant/system/string/operator_plus_equal/
---
## String::operator+=(char_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(char_t c)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要添加到目前字串末端的字元。 |

### 返回值

自身參考。

## String::operator+=(const String\&) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(const String &str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用於添加到目前字串的末端。 |

### 返回值

自身參考。

## String::operator+=(double) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(double value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | [Double](../../double/) 用於添加到目前字串的末端。 |

### 返回值

自身參考。

## String::operator+=(uint8_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(uint8_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint8_t** | [Byte](../../byte/) 用於添加到目前字串的末端。 |

### 返回值

自身參考。

## String::operator+=(int16_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(int16_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int16_t** | Short to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(uint16_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(uint16_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint16_t** | Unsigned short to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(int32_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(int32_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int32_t** | Int to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(uint32_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(uint32_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint32_t** | Unsigned int to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(int64_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(int64_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int64_t** | Long to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(uint64_t) 方法

串接賦值運算子。

```cpp
String & System::String::operator+=(uint64_t value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint64_t** | Unsigned long to add to the end of current string. |

### 返回值

自身參考。

## String::operator+=(T) 方法

串接賦值運算子。

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String & System::String::operator+=(T value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Value type to concatenate with string. Must be bool |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | [Boolean](../../boolean/) 用於添加到目前字串的末端。 |

### 返回值

自身參考。

## 參見

* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)