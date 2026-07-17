---
title: CompareTo()
second_title: Aspose.Slides for C++ API 参考
description: 比较当前对象和指定的对象。
type: docs
weight: 27
url: /zh/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const 方法

比较当前对象和指定的对象。

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeSpan](../) | 用于将当前对象与之比较的 [TimeSpan](../) 对象 |

### 返回值

- 1 表示当前对象的时间间隔短于 **value**；0 表示当前对象的时间间隔等于 **value**；1 表示当前对象的时间间隔长于 **value**

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const 方法

比较当前对象和指定的对象。

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 用于将当前对象与之比较的 [TimeSpan](../) 对象 |

### 返回值

- 1 表示当前对象的时间间隔短于 **value**；0 表示当前对象的时间间隔等于 **value**；1 表示当前对象的时间间隔长于 **value**

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [TimeSpan](../)
* 类 [Object](../../object/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)