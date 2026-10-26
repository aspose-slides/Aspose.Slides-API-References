---
title: CompareTo()
second_title: Aspose.Slides for C++ API 参考
description: 比较当前对象和 DateTime 类的指定实例所表示的两个日期时间值，并返回指示这些值在时间轴上相对位置的值。
type: docs
weight: 443
url: /zh/system/datetime/compareto/
---
## DateTime::CompareTo(DateTime) const 方法

比较当前对象和 [DateTime](../) 类的指定实例所表示的两个日期时间值，并返回指示这些值在时间轴上相对位置的值。

```cpp
constexpr int System::DateTime::CompareTo(DateTime value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../) | 用于与当前对象进行比较的 [DateTime](../) 类实例 |

### 返回值

返回值为负数（小于0）表示当前对象表示的时间早于 **value** 所表示的时间；0 表示两个对象表示的时间相同；大于0 的值表示当前对象表示的时间晚于 **value** 所表示的时间

## 另请参见

* 类 [DateTime](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)