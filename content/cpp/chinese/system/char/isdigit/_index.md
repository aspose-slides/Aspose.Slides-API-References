---
title: IsDigit()
second_title: Aspose.Slides C++ API 参考
description: 确定在指定字符缓冲区的指定索引处的字符是否被归类为十进制数字。
type: docs
weight: 79
url: /zh/system/char/isdigit/
---
## Char::IsDigit(const char_t *, int) 方法

确定在指定字符缓冲区的指定索引处的字符是否被归类为十进制数字。

```cpp
static bool System::Char::IsDigit(const char_t *str, int idx)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 要测试的字符在指定缓冲区中的零基索引 |

### 返回值

如果指定索引处的字符是十进制数字，则为 True，否则为 false

## Char::IsDigit(const String\&, const int32_t) 方法

确定在指定字符串的指定索引处的字符是否被归类为十进制数字。

```cpp
static bool System::Char::IsDigit(const String &str, const int32_t idx)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 一个字符串 |
| idx | const **int32_t** | 要测试的字符在指定缓冲区中的零基索引 |

### 返回值

如果指定索引处的字符是十进制数字，则为 True，否则为 false

## Char::IsDigit(char_t) 方法

确定指定字符是否被归类为十进制数字。

```cpp
static bool System::Char::IsDigit(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是十进制数字，则为 True，否则为 false

## 另见

* Class [Char](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)