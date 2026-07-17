---
title: operator>>()
second_title: Aspose.Slides for C++ API 参考
description: 使用 UTF-8 编码从输入流获取字符串。
type: docs
weight: 2965
url: /zh/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) 函数

从输入流获取字符串，使用 UTF-8 编码。

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in | std::istream\& | 输入流对象（**basic_ostream** 使用 **char** 实例化）。 |
| str | [String](../string/)\& | 从输入流读取的字符串。 |

### 返回值

一个已提取字符串的输入流。

## System::operator>>(std::wistream\&, String\&) 函数

从输入流获取字符串。

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in | std::wistream\& | 输入流对象（**basic_ostream** 使用 ****wchar_t**** 实例化）。 |
| str | [String](../string/)\& | 从输入流读取的字符串。 |

### 返回值

一个已提取字符串的输入流。

## 参见

* 类 [String](../string/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)