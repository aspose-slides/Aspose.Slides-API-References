---
title: IsUpper()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定字符串中指定索引处的字符是否被归类为大写字母。
type: docs
weight: 183
url: /zh/system/char/isupper/
---
## Char::IsUpper(const String\&, int) 方法

确定指定字符串中指定索引处的字符是否被分类为大写字母。

```cpp
static bool System::Char::IsUpper(const String &str, int idx)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | 包含该字符的字符串。 |
| idx | int | 要测试的指定字符串中的零基索引。 |

### 返回值

如果指定索引处的字符是大写字母，则返回 true；否则返回 false

## Char::IsUpper(const char_t *, int) 方法

确定指定字符缓冲区中指定索引处的字符是否被分类为大写字母。

```cpp
static bool System::Char::IsUpper(const char_t *str, int idx)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 要测试的指定缓冲区中字符的零基索引 |

### 返回值

如果指定索引处的字符是大写字母，则返回 true；否则返回 false

## Char::IsUpper(char_t) 方法

确定指定字符是否被分类为大写字母。

```cpp
static bool System::Char::IsUpper(char_t c)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是大写字母，则返回 true；否则返回 false

## 另见

* 类 [String](../../string/)
* 类 [Char](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)