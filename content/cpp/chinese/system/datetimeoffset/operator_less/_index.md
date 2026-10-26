---
title: operator<()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象表示的日期和时间值是否早于指定的 DateTimeOffset 对象所表示的值。
type: docs
weight: 560
url: /zh/system/datetimeoffset/operator_less/
---
## DateTimeOffset::operator<(const DateTimeOffset\&) const method

确定当前对象表示的日期和时间值是否早于指定的 [DateTimeOffset](../) 对象所表示的值。

```cpp
bool System::DateTimeOffset::operator<(const DateTimeOffset &other) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 用于将当前对象与之比较的 [DateTimeOffset](../) 对象 |

### 返回值

如果当前对象表示的日期和时间值早于 **other** 所表示的值，则返回 true；否则返回 false

## DateTimeOffset::operator<(std::nullptr_t) const method

```cpp
constexpr bool System::DateTimeOffset::operator<(std::nullptr_t) const
```

## 另请参见

* 类 [DateTimeOffset](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)