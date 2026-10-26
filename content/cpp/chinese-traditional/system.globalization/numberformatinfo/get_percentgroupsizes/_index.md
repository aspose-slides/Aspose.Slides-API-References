---
title: get_PercentGroupSizes()
second_title: Aspose.Slides for C++ API 參考
description: 取得每個百分比值群組的位數。
type: docs
weight: 612
url: /zh-hant/system.globalization/numberformatinfo/get_percentgroupsizes/
---
## NumberFormatInfo::get_PercentGroupSizes() const 方法


取得每個百分比值群組的位數。

```cpp
ArrayPtr<int> System::Globalization::NumberFormatInfo::get_PercentGroupSizes() const
```


### 返回值

[Array](../../../system/array/) 每組的位數，從左至右；每個元素必須是 1 到 9，最後一個可以是 0，表示「全部合併」；最後的元素會重複。

## 參見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [NumberFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)