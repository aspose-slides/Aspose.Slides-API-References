---
title: operator>()
second_title: Aspose.Slides C++ API 参考
description: 确定当前对象表示的时间间隔是否长于指定对象表示的时间间隔。
type: docs
weight: 404
url: /zh/system/timespan/operator_greater/
---
## TimeSpan::operator>(TimeSpan) const 方法

确定当前对象表示的时间间隔是否长于指定对象表示的时间间隔。

```cpp
constexpr bool System::TimeSpan::operator>(TimeSpan value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeSpan](../) | 用于将当前对象与 [TimeSpan](../) 对象进行比较的对象 |

### 返回值

如果当前对象表示的时间间隔长于 **value** 表示的时间间隔，则为 true；否则为 false

## TimeSpan::operator>(std::nullptr_t) const 方法

```cpp
constexpr bool System::TimeSpan::operator>(std::nullptr_t) const
```

## 另见

* 类 [TimeSpan](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)