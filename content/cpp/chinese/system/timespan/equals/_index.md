---
title: Equals()
second_title: Aspose.Slides C++ API 参考
description: 确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。
type: docs
weight: 40
url: /zh/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const 方法

确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeSpan](../) | 与当前对象比较的 [TimeSpan](../) 对象 |

### 返回值

如果当前对象和指定对象表示相同的时间间隔，则返回 True，否则 - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const 方法

确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 与当前对象比较的 [TimeSpan](../) 对象 |

### 返回值

如果当前对象和指定对象表示相同的时间间隔，则返回 True，否则 - false

## TimeSpan::Equals(TimeSpan, TimeSpan) 方法

如果指定的对象表示相同的时间间隔，则返回 true，否则 - false。

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## 另请参见

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)