---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 DateTime 对象，该对象表示与指定的 DateTime 对象相同的滴数，并根据参数 kind 的指定表示本地时间、UTC 时间或两者皆非。
type: docs
weight: 833
url: /zh/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) 方法

构造一个新的 [DateTime](../) 对象，该对象表示与指定的 [DateTime](../) 对象相同的滴数，并根据参数 **kind** 的指定表示本地时间、UTC 时间或两者皆非。

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../) | 用于复制滴数的 [DateTime](../) 对象 |
| kind | [DateTimeKind](../../datetimekind/) | 指定新对象应表示本地时间、UTC 时间或两者皆非。 |

### 返回值

一个新的 [DateTime](../) 对象，表示与 **value** 相同的滴数，并且其 DateTimeKind 值由 **kind** 指定。

## 另请参阅

* 枚举 [DateTimeKind](../../datetimekind/)
* 类 [DateTime](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)