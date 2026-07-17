---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 参考
description: 搜索指定对象并返回整个列表中最后一次出现的零基索引。
type: docs
weight: 469
url: /zh/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T&) const 方法

搜索指定对象并返回整个列表中最后一次出现的零基索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T& | 要在列表中定位的对象 |

### 返回值

如果找到，则返回 item 在整个 [List](../) 中最后一次出现的零基索引；否则为 -1。

## List::LastIndexOf(const T&, int32_t) const 方法

搜索指定对象并返回 [List](../) 中从第一个元素到指定索引范围内最后一次出现的零基索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T& | 要在列表中定位的对象 |
| index | **int32_t** | 向后搜索的零基起始索引。 |

### 返回值

如果找到，则返回 item 在 [List](../) 中从第一个元素到 index 范围内最后一次出现的零基索引；否则为 -1。

## List::LastIndexOf(const T&, int32_t, int32_t) const 方法

搜索指定对象并返回 [List](../) 中包含指定数量元素且在指定索引结束的范围内最后一次出现的零基索引。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T& | 要在 [List](../) 中定位的对象 |
| index | **int32_t** | 向后搜索的零基起始索引。 |
| count | **int32_t** | 要搜索的区段中元素的数量。 |

### 返回值

如果找到，则返回 item 在 [List](../) 中包含 count 个元素且在 index 结束的范围内最后一次出现的零基索引；否则为 -1。

## 另见

* 类 [List](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)