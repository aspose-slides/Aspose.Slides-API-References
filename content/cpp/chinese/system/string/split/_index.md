---
title: Split()
second_title: Aspose.Slides for C++ API 参考
description: 按字符拆分字符串。
type: docs
weight: 768
url: /zh/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const method

按字符拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | 用于拆分字符串的字符。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(char_t, int32_t, StringSplitOptions) const method

按字符拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | 用于拆分字符串的字符。 |
| count | **int32_t** | 返回的子字符串的最大数量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(char_t, char_t, StringSplitOptions) const method

按两个字符之一拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separatorA | char_t | 用于拆分字符串的第一个字符。 |
| separatorB | char_t | 用于拆分字符串的第二个字符。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method

按指定的字符集合拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)的分隔字符。如果为空，则任何空白字符都视为分隔符。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method

按指定的字符集合拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)的分隔字符。如果为空，则任何空白字符都视为分隔符。 |
| count | **int32_t** | 返回的子字符串的最大数量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const String\&, StringSplitOptions) const method

按子字符串拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | 充当分隔符的子字符串。如果为空，则空白字符充当分隔符。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const String\&, int, StringSplitOptions) const method

按子字符串拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | 充当分隔符的子字符串。如果为空，则空白字符充当分隔符。 |
| count | int | 拆分数组中元素的最大数量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method

按子字符串拆分字符串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/)的分隔字符串。如果为空，则不进行拆分。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method

按子字符串拆分字符串。目前，仅支持零或一个元素的分隔符数组。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/)的分隔字符串。如果为空，则不进行拆分。 |
| count | int | 拆分数组中元素的最大数量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 拆分选项。 |

### 返回值

[Array](../../array/)的子字符串。

## 另请参见

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)