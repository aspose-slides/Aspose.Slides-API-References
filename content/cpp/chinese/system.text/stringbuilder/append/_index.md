---
title: Append()
second_title: Aspose.Slides for C++ API 参考
description: 向构建器添加字符。
type: docs
weight: 118
url: /zh/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) 方法

向构建器添加字符。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 字符值。 |

### 返回值

此指针。

## StringBuilder::Append(char_t, int) 方法

向构建器添加字符。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 字符值。 |
| count | int | 要重复插入字符的次数。 |

### 返回值

此指针。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) 方法

向构建器添加字符数组。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要添加的字符。 |

### 返回值

此指针。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) 方法


向构建器添加字符数组切片。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要添加的字符。 |
| startIndex | int | 切片的起始索引。 |
| charCount | int | 切片的长度。 |

### 返回值

此指针。

## StringBuilder::Append(const String\&) 方法


向构建器添加字符串。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于添加。 |

### 返回值

此指针。

## StringBuilder::Append(const String\&, int, int) 方法


向构建器添加字符串切片。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于添加。 |
| startIndex | int | 切片的起始索引。 |
| charCount | int | 切片的长度。 |

### 返回值

此指针。

## StringBuilder::Append(const SharedPtr\<T\>\&) 方法


向构建器添加对象的字符串表示。

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) 序列化并添加。 |

### 返回值

此指针。

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) 方法


向构建器添加另一个构建器的内容。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | 要从中添加内容的构建器。 |

### 返回值

此指针。

## StringBuilder::Append(float) 方法


向构建器添加浮点数值。

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| f | **float** | 要序列化并添加的值。 |

### 返回值

此指针。

## StringBuilder::Append(double) 方法


向构建器添加浮点数值。

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| df | **double** | 要序列化并添加的值。 |

### 返回值

此指针。

## StringBuilder::Append(int) 方法


向构建器添加整数值。

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | int | 要序列化并添加的值。 |

### 返回值

此指针。

## StringBuilder::Append(T) 方法


向构建器添加算术值。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 算术类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 要序列化并添加的值。 |

### 返回值

此指针。

## StringBuilder::Append(E) 方法


向构建器添加枚举值的字符串表示。

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| E | [Enum](../../../system/enum/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| e | E | 要序列化并添加的值。 |

### 返回值

此指针。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)