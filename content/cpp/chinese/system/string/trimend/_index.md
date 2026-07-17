---
title: TrimEnd()
second_title: Aspose.Slides for C++ API 参考
description: 从字符串末尾移除所有空白字符。
type: docs
weight: 703
url: /zh/system/string/trimend/
---
## String::TrimEnd() const 方法

从字符串末尾移除所有空白字符。

```cpp
String System::String::TrimEnd() const
```

### 返回值

[String](../) 没有前导空白字符。

## String::TrimEnd(char_t) const 方法

从字符串末尾移除所有传入字符的出现。

```cpp
String System::String::TrimEnd(char_t ch) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char_t | 要移除的符号。 |

### 返回值

移除结果。

## String::TrimEnd(const String\&) const 方法

从字符串末尾移除所有传入字符的出现。

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 的字符用于移除。 |

### 返回值

[String](../) 不含已移除的字符。

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const 方法

从字符串末尾移除所有传入字符的出现。

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 的字符用于移除。 |

### 返回值

[String](../) 不含已移除的字符。

## 参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)