---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: セルの集合を取得します。
type: docs
weight: 14
url: /ja/aspose.slides.charts/chartdataworkbook/getcellcollection/
---
## ChartDataWorkbook::GetCellCollection(System::String, bool) メソッド

セルの集合を取得します。

```cpp
System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::ChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) formula は "Sheet1!$A$2:$A$5" のようです。 |
| skipHiddenCells | **bool** | true の場合、メソッドは非表示セルを除いたコレクションを返します。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCellCollection](../../ichartcellcollection/)
* クラス [String](../../../system/string/)
* クラス [ChartDataWorkbook](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)