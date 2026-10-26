---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 将字符串插入构建器的固定位置。
type: docs
weight: 183
url: /zh/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) 方法

将字符串插入构建器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 插入字符的位置。 |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于插入。 |

### 返回值

This pointer.

## StringBuilder::Insert(int32_t, const String\&, int32_t) 方法

将重复的字符串插入构建器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入字符的位置。 |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于插入。 |
| count | **int32_t** | 要重复 **value** 字符串的次数。 |

### 返回值

This pointer.

## StringBuilder::Insert(int, char_t) 方法

将字符插入构建器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 插入字符的位置。 |
| ch | char_t | 要插入的字符。 |

### 返回值

This pointer.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) 方法

将字符插入构建器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入字符的位置。 |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) 用于插入切片来源。 |
| startIndex | int | [Array](../../../system/array/) 切片起始索引。 |
| charCount | int | [Array](../../../system/array/) 切片长度。 |

### 返回值

This pointer.

## StringBuilder::Insert(int, T) 方法

将值插入构建器的固定位置。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Parameter | 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 插入字符的位置。 |
| value | T | 要格式化并插入的值。 |

### 返回值

This pointer.

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [StringBuilder](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)