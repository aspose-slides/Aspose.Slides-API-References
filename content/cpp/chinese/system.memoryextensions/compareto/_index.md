---
title: CompareTo()
second_title: Aspose.Slides C++ API 参考
description: 比较两个字符跨度，使用指定的字符串比较规则。
type: docs
weight: 404
url: /zh/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数

比较两个字符跨度，使用指定的字符串比较规则。

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第一个字符跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第二个字符跨度 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要执行的字符串比较类型 |

### 返回值

如果 span < other 则返回负值，等于时返回零，span > other 时返回正值

## 另见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)