---
title: Trim()
second_title: Aspose.Slides for C++ API 参考
description: 删除字符串开头和结尾的所有空白字符。
type: docs
weight: 677
url: /zh/system/string/trim/
---
## String::Trim() const 方法

删除字符串开头和结尾的所有空白字符。

```cpp
String System::String::Trim() const
```

### 返回值

[String](../) 没有开头或结尾的空白。

## String::Trim(char_t) const 方法

删除字符串开头和结尾的传入字符的所有出现。

```cpp
String System::String::Trim(char_t ch) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char_t | 要删除的符号。 |

### 返回值

删除结果。

## String::Trim(const String\&) const 方法

删除字符串开头和结尾的传入字符的所有出现。

```cpp
String System::String::Trim(const String &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 要删除的字符。 |

### 返回值

[String](../) 不含已删除的字符。

## String::Trim(const ArrayPtr\<char_t\>\&) const 方法

删除字符串开头和结尾的传入字符的所有出现。

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要删除的字符。 |

### 返回值

[String](../) 不含已删除的字符。

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)