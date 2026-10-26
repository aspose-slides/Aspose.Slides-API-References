---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 相等比较运算符。
type: docs
weight: 300
url: /zh/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const method

相等比较运算符。

```cpp
bool System::String::operator==(const String &str) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用于将当前对象与其进行比较。 |

### 返回值

如果两个字符串均为 null 或均不为 null 且相等则返回 true，否则返回 false。

## String::operator==(std::nullptr_t) const method

检查字符串是否为 null。采用与 [IsNull()](../isnull/) 调用相同的逻辑。

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### 返回值

如果字符串为 null 则返回 true，否则返回 false。

## 另请参阅

* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)