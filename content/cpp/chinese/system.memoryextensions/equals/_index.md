---
title: Equals()
second_title: Aspose.Slides C++ API 参考
description: 使用 StringComparison 比较两个 ReadOnlySpan<char16_t> 是否相等。
type: docs
weight: 417
url: /zh/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数

使用 StringComparison 比较两个 ReadOnlySpan<char16_t> 是否相等。

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要比较的第一个 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要比较的第二个 span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要使用的字符串比较类型 |

## 返回值

如果 span 相等则返回 true，否则返回 false

## 另见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)