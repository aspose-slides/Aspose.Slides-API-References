---
title: operator+()
second_title: Aspose.Slides for C++ API 参考
description: 字符串连接运算符。
type: docs
weight: 274
url: /zh/system/string/operator_plus/
---
## String::operator+(const String\&) const 方法

[String](../) 连接运算符。

```cpp
String System::String::operator+(const String &str) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 添加到当前字符串的末尾。 |

### 返回值

连接后的字符串。

## String::operator+(const T\&) const 方法

[String](../) 与字符串文字或字符字符串指针的连接。

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 字符串文字或字符字符串指针形式之一。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg | const T\& | 与当前字符串连接的实体。 |

### 返回值

连接后的字符串。

## String::operator+(char_t) const 方法

向字符串末尾添加字符。

```cpp
String System::String::operator+(char_t x) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | char_t | 要添加的字符。 |

### 返回值

[String](../) 连接结果。

## String::operator+(int) const 方法

向字符串末尾添加整数值的字符串表示。

```cpp
String System::String::operator+(int i) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | int | 要转换为字符串并添加的整数值。 |

### 返回值

[String](../) 连接结果。

## String::operator+(uint32_t) const 方法

向字符串末尾添加无符号整数值的字符串表示。

```cpp
String System::String::operator+(uint32_t i) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **uint32_t** | 要转换为字符串并添加的值。 |

### 返回值

[String](../) 连接结果。

## String::operator+(double) const 方法

向字符串末尾添加浮点值的字符串表示。

```cpp
String System::String::operator+(double d) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | **double** | 要转换为字符串并添加的值。 |

### 返回值

[String](../) 连接结果。

## String::operator+(int64_t) const 方法

向字符串末尾添加整数值的字符串表示。

```cpp
String System::String::operator+(int64_t v) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | **int64_t** | 要转换为字符串并添加的值。 |

### 返回值

[String](../) 连接结果。

## String::operator+(const T\&) const 方法

向字符串末尾添加引用类型对象的字符串表示。

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 指针类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) 使用 [ToString()](../tostring/) 调用将其转换为字符串并添加到当前字符串。 |

### 返回值

[String](../) 连接结果。

## String::operator+(const T\&) const 方法

向字符串末尾添加值类型对象的字符串表示。

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型，需在其上调用 [ToString()](../tostring/)。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) 使用 [ToString()](../tostring/) 调用将其转换为字符串并添加到当前字符串。 |

### 返回值

[String](../) 连接结果。

## String::operator+(T) const 方法

向字符串末尾添加布尔值的字符串表示。

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 与字符串连接的值类型。必须是 bool |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) 值，将其转换为字符串并添加。 |

### 返回值

[String](../) 连接结果。

## 另见

* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)