---
title: get_PercentGroupSizes()
second_title: Aspose.Slides C++ API 参考
description: 获取每个百分比值组的数字位数。
type: docs
weight: 612
url: /zh/system.globalization/numberformatinfo/get_percentgroupsizes/
---
## NumberFormatInfo::get_PercentGroupSizes() const 方法


获取每个百分比值组的数字位数。

```cpp
ArrayPtr<int> System::Globalization::NumberFormatInfo::get_PercentGroupSizes() const
```


### 返回值

[Array](../../../system/array/) 每组的数字位数，从左到右；每个元素必须为 1 到 9，最后一个可以为 0，表示 \"全部合并\"；最后一个元素会重复。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [NumberFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)