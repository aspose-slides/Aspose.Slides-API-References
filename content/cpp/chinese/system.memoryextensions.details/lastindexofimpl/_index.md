---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API 参考
description: 在 span 中查找值的最后索引。
type: docs
weight: 14
url: /zh/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) 函数


在 span 中查找值的最后索引。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) 用于搜索 |
| length | **int32_t** | 搜索范围的长度 |
| value | const T\& | 要查找的值 |

### 返回值

值的最后索引，如果未找到则返回 **-1**

## 参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)