---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: セルの集合を取得します。
type: docs
weight: 27
url: /ja/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) メソッド

セルの集合を取得します。

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) のような式 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | true の場合、メソッドは非表示セルを除いたコレクションを返します。 |

### Return Value

セルの集合 [IChartCellCollection](../../ichartcellcollection/)

## See Also

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCellCollection](../../ichartcellcollection/)
* クラス [String](../../../system/string/)
* クラス [IChartDataWorkbook](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)