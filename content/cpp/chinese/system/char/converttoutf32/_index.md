---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的 UTF-16 代理对转换为 UTF-32 代码单元。
type: docs
weight: 287
url: /zh/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) 方法

将指定的 UTF-16 代理对转换为 UTF-32 代码单元。

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| highSurrogate | char_t | 要转换的 UTF-16 代理对的高位代理 |
| lowSurrogate | char_t | 要转换的 UTF-16 代理对的低位代理 |

### 返回值

转换后得到的 UTF-32 代码单元

## Char::ConvertToUtf32(const String\&, int) 方法

将字符串中指定位置的 UTF-16 编码字符或代理对的值转换为 UTF-32 代码单元。

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 包含字符或代理对的字符串 |
| index | int | 指定字符串中字符或代理对的索引位置 |

### 返回值

转换后得到的 UTF-32 代码单元

## 另见

* 类 [Char](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)