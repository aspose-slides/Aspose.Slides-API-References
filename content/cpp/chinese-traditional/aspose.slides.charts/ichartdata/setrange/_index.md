---
title: SetRange()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定圖表資料範圍。Series 和 categories 會根據新的資料範圍進行更新。如果資料範圍中的 series 數量大於圖表資料中的 series 數量，則會在目前集合的末端新增與最後一個 series 相同類型的額外 series。
type: docs
weight: 157
url: /zh-hant/aspose.slides.charts/ichartdata/setrange/
---
## IChartData::SetRange(System::String) 方法

設定圖表資料範圍。Series 和 categories 將根據新的資料範圍進行更新。如果資料範圍中的 series 數量大於圖表資料中的 series 數量，則會在集合的末端新增與目前集合中最後一個 series 具有相同類型的額外 series。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetRange(System::String formula)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 儲存格資料範圍公式。例如：\"Sheet1!$A$1:$C$4\"、\"SomeSheetName!A1:B100\"、\"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\"。 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)