---
title: GetStringComparer()
second_title: Aspose.Slides for C++ API 参考
description: 获取针对指定 CompareInfo 对象和指定字符串比较规则的 StringComparer 对象。
type: docs
weight: 1
url: /zh/system.globalization/globalizationextensions/getstringcomparer/
---
## GlobalizationExtensions::GetStringComparer(const CompareInfoPtr\&, CompareOptions) 方法

获取 [StringComparer](../../../system/stringcomparer/) 对象，以针对指定的 [CompareInfo](../../compareinfo/) 对象和指定的字符串比较规则。

```cpp
static StringComparerPtr System::Globalization::GlobalizationExtensions::GetStringComparer(const CompareInfoPtr &compare_info, CompareOptions options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| compare_info | const [CompareInfoPtr](../../compareinfoptr/)\& | [CompareInfo](../../compareinfo/) 对象。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比较选项。 |

### 返回值

[StringComparer](../../../system/stringcomparer/) 对象。

## 另见

* 枚举 [CompareOptions](../../compareoptions/)
* 类型定义 [StringComparerPtr](../../../system/stringcomparerptr/)
* 类型定义 [CompareInfoPtr](../../compareinfoptr/)
* 类 [GlobalizationExtensions](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)