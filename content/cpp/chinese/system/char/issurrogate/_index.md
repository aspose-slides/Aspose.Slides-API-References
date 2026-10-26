---
title: IsSurrogate()
second_title: Aspose.Slides C++ API 参考
description: 确定指定字符是否为 UTF-16 代理码单元。
type: docs
weight: 14
url: /zh/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) method


确定指定字符是否为 UTF-16 代理码单元。

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 一个字符 |

### 返回值

如果指定字符是 UTF-16 代理码单元则返回 True，否则返回 false

## Char::IsSurrogate(const String\&, int) method


确定指定字符串中指定索引处的字符是否为 UTF-16 代理码单元。

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 一个字符串 |
| index | int | 指定字符串中字符的索引 |

### 返回值

如果指定索引处的字符是 UTF-16 代理码单元则返回 True，否则返回 false

## 参见

* 类 [Char](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)