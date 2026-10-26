---
title: SetRange()
second_title: Aspose.Slides for C++ API 參考
description: 設定圖表資料範圍。系列和類別會根據新的資料範圍進行更新。如果資料範圍中的系列數量大於圖表資料中的系列計數，則會在目前集合的末端新增與最後一個系列相同類型的系列。
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) 方法

設定圖表資料範圍。系列和類別會根據新的資料範圍進行更新。如果資料範圍中的系列數量大於圖表資料中的系列計數，則會在目前集合的末端新增與最後一個系列相同類型的系列。

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)