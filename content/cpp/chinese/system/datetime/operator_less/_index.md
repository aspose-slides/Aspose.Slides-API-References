---
title: operator<()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象表示的日期和时间值是否早于由指定 DateTime 对象表示的值。
type: docs
weight: 586
url: /zh/system/datetime/operator_less/
---
## DateTime::operator<(DateTime) const 方法

确定当前对象表示的日期和时间值是否早于由指定 [DateTime](../) 对象表示的值。

```cpp
constexpr bool System::DateTime::operator<(DateTime other) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [DateTime](../) | 用于与当前对象比较的 [DateTime](../) 对象 |

### 返回值

如果当前对象表示的日期和时间值早于 **other** 表示的值，则返回 True，否则返回 false

## DateTime::operator<(std::nullptr_t) const 方法

```cpp
constexpr bool System::DateTime::operator<(std::nullptr_t) const
```

## 另见

* 类 [DateTime](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)