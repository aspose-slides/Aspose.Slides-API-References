---
title: TrimStart()
second_title: Aspose.Slides C++ API 参考
description: 从字符串开头移除所有空白字符。
type: docs
weight: 690
url: /zh/system/string/trimstart/
---
## String::TrimStart() const 方法

从字符串的开头移除所有空白字符。

```cpp
String System::String::TrimStart() const
```

### 返回值

[String](../)，开头没有空白字符。

## String::TrimStart(char_t) const 方法

从字符串的开头移除传入字符的所有出现。

```cpp
String System::String::TrimStart(char_t ch) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char_t | 要移除的符号。 |

### 返回值

移除结果。

## String::TrimStart(const String\&) const 方法

从字符串的开头移除传入字符的所有出现。

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../)要移除的字符。 |

### 返回值

[String](../)，没有被移除的字符。

## String::TrimStart(const ArrayPtr\<char_t\>\&) const 方法

从字符串的开头移除传入字符的所有出现。

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)要移除的字符。 |

### 返回值

[String](../)，没有被移除的字符。

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)