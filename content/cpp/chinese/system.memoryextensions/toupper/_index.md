---
title: ToUpper()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的文化将字符转换为大写。
type: docs
weight: 469
url: /zh/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 函数

使用指定的文化将字符转换为大写。

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要转换的源字符跨度 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用于存储转换后字符的目标跨度 |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 用于转换的文化（nullptr 表示当前文化） |

## 返回值

已转换字符的数量，或者如果目标太小则返回 -1

## 另见

* 类型别名 [SharedPtr](../../system/sharedptr/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 类 [CultureInfo](../../system.globalization/cultureinfo/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)