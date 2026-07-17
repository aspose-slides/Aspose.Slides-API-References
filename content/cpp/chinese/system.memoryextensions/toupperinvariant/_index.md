---
title: ToUpperInvariant()
second_title: Aspose.Slides C++ API 参考
description: 使用不变区域设置将字符转换为大写。
type: docs
weight: 482
url: /zh/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 函数


将字符转换为不变区域设置的大写形式。

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要转换的源字符跨度 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 存储已转换字符的目标跨度 |

### 返回值

已转换的字符数，如果目标太小则返回 -1

## 参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)