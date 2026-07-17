---
title: Compare()
second_title: Aspose.Slides for C++ API 参考
description: 比较由指定的 DateTime 类实例表示的两个值，并返回指示这些值在时间线上相对位置的值。
type: docs
weight: 846
url: /zh/system/datetime/compare/
---
## DateTime::Compare(DateTime, DateTime) 方法

比较由指定的 [DateTime](../) 类实例表示的两个值，并返回指示这些值在时间线上相对位置的值。

```cpp
static constexpr int System::DateTime::Compare(DateTime t1, DateTime t2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| t1 | [DateTime](../) | 第一个比较项 |
| t2 | [DateTime](../) | 第二个比较项 |

### 返回值

如果 **t1** 早于 **t2**，则返回值小于 0；如果 **t1** 与 **t2** 相同，则返回值为 0；如果 **t1** 晚于 **t2**，则返回值大于 0

## 另请参见

* 类 [DateTime](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)