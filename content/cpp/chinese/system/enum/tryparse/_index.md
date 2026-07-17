---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将指定的字符串转换为等价的枚举常量。
type: docs
weight: 79
url: /zh/system/enum/tryparse/
---
## Enum::TryParse(const String&, E&) 方法

尝试将指定的字符串转换为等价的枚举常量。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) 被解释为包含枚举常量的名称 |
| result | E\& | 如果转换成功，则该输出参数包含函数的转换结果 |

### 返回值

如果转换成功则返回 True，否则返回 false

## Enum::TryParse(const String&, bool, E&) 方法

尝试将指定的字符串转换为等价的枚举常量。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) 被解释为包含枚举常量的名称 |
| ignoreCase | **bool** | 指定在解释字符串时是否应忽略大小写 |
| result | E\& | 如果转换成功，则该输出参数包含函数返回的转换结果 |

### 返回值

如果转换成功则返回 True，否则返回 false

## 另请参阅

* 类 [String](../../string/)
* 结构体 [Enum](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)