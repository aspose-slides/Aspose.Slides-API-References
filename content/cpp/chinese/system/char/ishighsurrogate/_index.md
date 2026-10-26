---
title: IsHighSurrogate()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定字符串中指定索引处的字符是否为 UTF-16 高代理代码单元。
type: docs
weight: 40
url: /zh/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) 方法

确定指定字符串中指定索引处的字符是否为 UTF-16 高代理代码单元。

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 字符串 |
| index | int | 在指定字符串中要测试的字符的索引 |

### 返回值

如果指定索引处的字符是 UTF-16 高代理代码单元，则返回 true；否则返回 false

## Char::IsHighSurrogate(const char_t *, int) 方法

确定指定字符缓冲区中指定索引处的字符是否为高代理。

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 在指定缓冲区中要测试的字符的零基索引 |

### 返回值

如果指定索引处的字符是高代理，则返回 true；否则返回 false

## Char::IsHighSurrogate(char_t) 方法

确定指定字符是否为高代理。

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是高代理，则返回 true；否则返回 false

## 另请参见

* 类 [String](../../string/)
* 类 [Char](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)