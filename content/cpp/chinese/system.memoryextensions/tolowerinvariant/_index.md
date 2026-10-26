---
title: ToLowerInvariant()
second_title: Aspose.Slides C++ API 参考
description: 使用不变区域性将字符转换为小写。
type: docs
weight: 456
url: /zh/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 函数

使用不变区域性将字符转换为小写。

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要转换的源字符跨度 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用于存储转换后字符的目标跨度 |

### 返回值

已转换的字符数量，如果目标跨度太小则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)