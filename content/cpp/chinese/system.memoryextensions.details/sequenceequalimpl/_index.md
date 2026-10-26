---
title: SequenceEqualImpl()
second_title: Aspose.Slides C++ API 参考
description: 检查两个 span 是否从指定位置开始相等。
type: docs
weight: 27
url: /zh/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) 函数

检查两个 span 是否从指定位置开始相等。

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一个 span |
| start | const **int32_t** | 第一个 span 中的起始索引 |
| length | **int32_t** | 要比较的元素数量 |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二个 span |

### 返回值

如果指定的范围相等则返回 true，否则返回 false

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)