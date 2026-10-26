---
title: IsWhiteSpace()
second_title: Aspose.Slides for C++ API 参考
description: 确定在指定字符缓冲区中指定索引处的字符是否被归类为空白字符。
type: docs
weight: 157
url: /zh/system/char/iswhitespace/
---
## Char::IsWhiteSpace(const char_t *, int) 方法

确定指定字符缓冲区中指定索引处的字符是否被归类为空白字符。

```cpp
static bool System::Char::IsWhiteSpace(const char_t *str, int idx)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 要测试的字符在指定缓冲区中的零基索引 |

### 返回值

如果指定索引处的字符是空白字符，则返回 true；否则返回 false

## Char::IsWhiteSpace(char_t) 方法

确定指定字符是否被归类为空白字符。

```cpp
static bool System::Char::IsWhiteSpace(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是空白字符，则返回 true；否则返回 false

## Char::IsWhiteSpace(const String\&, int) 方法

确定指定字符串中指定索引处的字符是否被归类为空白字符。

```cpp
static bool System::Char::IsWhiteSpace(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 字符串 |
| index | int | 要测试的字符在指定字符串中的零基索引 |

### 返回值

如果指定索引处的字符是空白字符，则返回 true；否则返回 false

## 参见

* 类 [Char](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)