---
title: ToLower()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的区域性将字符转换为小写。
type: docs
weight: 443
url: /zh/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 函数


使用指定的区域性将字符转换为小写。

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要转换的源字符跨度 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 存储转换后字符的目标跨度 |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 用于转换的区域性（nullptr 表示当前区域性） |

### 返回值

转换的字符数，若目标跨度太小则返回 -1

## 参见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 类 [CultureInfo](../../system.globalization/cultureinfo/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)