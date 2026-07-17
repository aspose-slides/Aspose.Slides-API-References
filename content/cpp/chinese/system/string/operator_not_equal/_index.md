---
title: operator!=()
second_title: Aspose.Slides C++ API 参考
description: 不等比较运算符。
type: docs
weight: 313
url: /zh/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const 方法

不等比较运算符。

```cpp
bool System::String::operator!=(const String &str) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用于将当前对象与之比较。 |

### 返回值

false if both strings are null or both are not null and match, true otherwise.

## String::operator!=(std::nullptr_t) const 方法

检查字符串是否不为 null。应用与 [IsNull()](../isnull/) 调用相同的逻辑。

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### 返回值

false if string is null, true otherwise.

## 参见

* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)