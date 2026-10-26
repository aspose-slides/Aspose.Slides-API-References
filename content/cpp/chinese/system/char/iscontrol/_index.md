---
title: IsControl()
second_title: Aspose.Slides for C++ API 参考
description: 确定在指定字符缓冲区中指定索引处的字符是否被分类为 Unicode 控制字符。
type: docs
weight: 66
url: /zh/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) 方法

确定指定字符缓冲区中指定索引处的字符是否被分类为 Unicode 控制字符。

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字符缓冲区起始位置的指针 |
| idx | int | 要测试的字符在指定缓冲区中的零基索引 |

### 返回值

如果指定索引处的字符是 Unicode 控制字符，则为 True；否则为 false

## Char::IsControl(char_t) 方法

确定指定字符是否被分类为 Unicode 控制字符。

```cpp
static bool System::Char::IsControl(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要测试的字符 |

### 返回值

如果指定字符是 Unicode 控制字符，则为 True；否则为 false

## 另请参阅

* 类 [Char](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)