---
title: set_PercentGroupSizes()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定每個百分比值群組的位數。
type: docs
weight: 625
url: /zh-hant/system.globalization/numberformatinfo/set_percentgroupsizes/
---
## NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr\<int\>\&) 方法


設定每個百分比值群組的位數。

```cpp
void System::Globalization::NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr<int> &value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [ArrayPtr](../../../system/arrayptr/)\<int\>\& | [Array](../../../system/array/) 每組的位數，從左至右；每個元素必須是 1 到 9，最後一個可以是 0，表示「\"全部合併\"」；最後一個元素會重複。 |

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [NumberFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)