---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 尝试将仅包含单个字符的字符串转换为 UTF-16 字符。仅当输入字符串非空且长度恰好为一个字符时，函数才会成功。
type: docs
weight: 300
url: /zh/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) 方法

尝试将仅包含单个字符的字符串转换为 UTF-16 字符。仅当输入字符串非空且长度恰好为一个字符时，函数才会成功。

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) 用于转换 |
| result | char_t\& | 如果转换成功，输出变量将包含转换结果 |

### 返回值

如果转换成功则返回 true，否则返回 false

## 参见

* 类 [String](../../string/)
* 类 [Char](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)