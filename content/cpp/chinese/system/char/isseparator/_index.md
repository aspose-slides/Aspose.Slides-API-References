---
title: IsSeparator()
second_title: Aspose.Slides C++ API 参考
description: 确定在指定字符缓冲区的指定索引处的字符是否被分类为分隔符字符。
type: docs
weight: 131
url: /zh/system/char/isseparator/
---
## Char::IsSeparator(const char_t *, int) 方法


确定在指定字符缓冲区的指定索引处的字符是否被分类为分隔符字符。

```cpp
static bool System::Char::IsSeparator(const char_t *str, int idx)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 要测试的字符在指定缓冲区中的零基索引 |

### 返回值

如果指定索引处的字符是分隔符字符，则返回 True；否则返回 false

## Char::IsSeparator(char_t) 方法


确定指定字符是否被分类为分隔符字符。

```cpp
static bool System::Char::IsSeparator(char_t c)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是分隔符字符，则返回 True；否则返回 false

## 另见

* 类 [Char](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)