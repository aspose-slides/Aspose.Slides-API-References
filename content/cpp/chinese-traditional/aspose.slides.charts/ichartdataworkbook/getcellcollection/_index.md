---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得儲存格集合。
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) 方法

取得儲存格集合。

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) 公式，如 \"Sheet1!$A$2:$A$5\"。 |
| skipHiddenCells | **bool** | 如果為 true，則方法返回不含隱藏儲存格的集合。 |

### 返回值

儲存格集合 [IChartCellCollection](../../ichartcellcollection/)

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Class [IChartDataWorkbook](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)