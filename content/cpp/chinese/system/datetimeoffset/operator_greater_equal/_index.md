---
title: operator>=()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象表示的日期和时间值是否晚于或等于指定的 DateTimeOffset 对象所表示的值。
type: docs
weight: 599
url: /zh/system/datetimeoffset/operator_greater_equal/
---
## DateTimeOffset::operator>=(const DateTimeOffset\&) const 方法

确定当前对象表示的日期时间值是否晚于或等于指定的 [DateTimeOffset](../) 对象所表示的值。

```cpp
bool System::DateTimeOffset::operator>=(const DateTimeOffset &other) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 用于与当前对象进行比较的 [DateTimeOffset](../) 对象 |

### 返回值

如果当前对象表示的日期时间值晚于或等于 **other** 所表示的值，则为 True；否则 - false

## DateTimeOffset::operator>=(std::nullptr_t) const 方法

```cpp
constexpr bool System::DateTimeOffset::operator>=(std::nullptr_t) const
```

## 另见

* 类 [DateTimeOffset](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)