---
title: IsSurrogatePair()
second_title: Aspose.Slides C++ API 参考
description: 确定两个指定字符是否为 UTF-16 代理对。
type: docs
weight: 27
url: /zh/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) 方法

确定两个指定字符是否为 UTF-16 代理对。

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| highSurrogate | char_t | 待测试是否为高代理的字符 |
| lowSurrogate | char_t | 待测试是否为低代理的字符 |

### 返回值

如果指定字符构成代理对则返回 true，否则返回 false

## Char::IsSurrogatePair(const String\&, int) 方法

确定指定字符缓冲区中连续的两个字符是否为代理对。

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 字符串 |
| index | int | 指定缓冲区中测试字符序列开始处的零基索引 |

### 返回值

如果指定字符构成代理对则返回 true，否则返回 false

## 参见

* 类 [Char](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)