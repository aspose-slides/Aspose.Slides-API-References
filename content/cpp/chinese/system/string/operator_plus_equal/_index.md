---
title: operator+=()
second_title: Aspose.Slides for C++ API 参考
description: 连接赋值运算符。
type: docs
weight: 287
url: /zh/system/string/operator_plus_equal/
---
## String::operator+=(char_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要添加到当前字符串末尾的字符。 |

### 返回值

self reference.

## String::operator+=(const String\&) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 添加到当前字符串的末尾。 |

### 返回值

self reference.

## String::operator+=(double) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | [Double](../../double/) 添加到当前字符串的末尾。 |

### 返回值

self reference.

## String::operator+=(uint8_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(uint8_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint8_t** | [Byte](../../byte/) 添加到当前字符串的末尾。 |

### 返回值

self reference.

## String::operator+=(int16_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(int16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int16_t** | Short to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(uint16_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(uint16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint16_t** | Unsigned short to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(int32_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(int32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | Int to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(uint32_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | Unsigned int to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(int64_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | Long to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(uint64_t) 方法

连接赋值运算符。

```cpp
String & System::String::operator+=(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | Unsigned long to add to the end of current string. |

### 返回值

self reference.

## String::operator+=(T) 方法

连接赋值运算符。

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String & System::String::operator+=(T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Value type to concatenate with string. Must be bool |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | [Boolean](../../boolean/) 添加到当前字符串的末尾。 |

### 返回值

self reference.

## 另见

* 类 [String](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)