---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的字符串转换为 bool 类型的值。
type: docs
weight: 14
url: /zh/system/boolean/tryparse/
---
## Boolean::TryParse(const String\&, bool\&) 方法

将指定的字符串转换为 bool 类型的值。

```cpp
static bool System::Boolean::TryParse(const String &value, bool &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **bool**\& | 转换结果的引用，指向一个 bool 变量；如果指定的字符串等于 "True" 则结果为 true；如果等于 "False" 则结果为 false。 |

### 返回值

如果指定的字符串等于 "True" 或 "False" 则返回 true，否则返回 false。

## 另见

* 类 [String](../../string/)
* 类 [Boolean](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)