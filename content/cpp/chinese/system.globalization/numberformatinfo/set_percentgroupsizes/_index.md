---
title: set_PercentGroupSizes()
second_title: Aspose.Slides for C++ API 参考
description: 设置每个百分比值组的数字位数。
type: docs
weight: 625
url: /zh/system.globalization/numberformatinfo/set_percentgroupsizes/
---
## NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr\<int\>\&) 方法

设置每个百分比值组的数字位数。

```cpp
void System::Globalization::NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr<int> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [ArrayPtr](../../../system/arrayptr/)\<int\>\& | [Array](../../../system/array/) 每组的数字位数，从左到右；每个元素必须是 1 到 9，最后一个可以是 0，表示 \"合并所有\"；最后一个元素重复。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [NumberFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)