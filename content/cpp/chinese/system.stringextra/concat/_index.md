---
title: Concat()
second_title: Aspose.Slides for C++ API 参考
description: 连接字符串数组。
type: docs
weight: 1
url: /zh/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) 函数


连接字符串数组。

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) 的字符串用于连接。 |

### 返回值

连接后的字符串。

## System::StringExtra::Concat(const String\&, const String\&) 函数


连接字符串。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一个要连接的字符串。 |
| str1 | const [String](../../system/string/)\& | 第二个要连接的字符串。 |

### 返回值

连接的参数字符串。

## System::StringExtra::Concat(const String\&, const String\&, const String\&) 函数


连接字符串。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一个要连接的字符串。 |
| str1 | const [String](../../system/string/)\& | 第二个要连接的字符串。 |
| str2 | const [String](../../system/string/)\& | 第三个要连接的字符串。 |

### 返回值

连接的参数字符串。

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) 函数


连接字符串。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一个要连接的字符串。 |
| str1 | const [String](../../system/string/)\& | 第二个要连接的字符串。 |
| str2 | const [String](../../system/string/)\& | 第三个要连接的字符串。 |
| str3 | const [String](../../system/string/)\& | 第四个要连接的字符串。 |

### 返回值

连接的参数字符串。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函数


将多个对象转换为字符串并连接所得字符串。针对 [SmartPtr](../../system/smartptr/) 类型的特化。

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 用于转换并连接。 |

### 返回值

[String](../../system/string/) 值，由所有传入对象的字符串表示连接而成。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函数


将多个对象转换为字符串并连接所得字符串。针对算术类型的特化。

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 用于转换并连接。 |

### 返回值

[String](../../system/string/) 值，由所有传入对象的字符串表示连接而成。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函数


将多个对象转换为字符串并连接所得字符串。针对结构体和其他值类型的特化。

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 用于转换并连接。 |

### 返回值

[String](../../system/string/) 值，由所有传入对象的字符串表示连接而成。

## 另请参见

* Typedef [ArrayPtr](../../system/arrayptr/)
* 类 [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* 命名空间 [System::StringExtra](../)
* Library [Aspose.Slides](../../)