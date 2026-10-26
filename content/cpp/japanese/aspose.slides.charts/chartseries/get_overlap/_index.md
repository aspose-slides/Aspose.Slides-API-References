---
title: get_Overlap()
second_title: Aspose.Slides for C++ API リファレンス
description: 2-D チャートの棒と列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対しても適用されます。親シリーズ グループの対応するプロパティの投影であるため、このプロパティは読み取り専用です。値を変更するには、get_ParentSeriesGroup()->Overlap() 読み書き可能プロパティを使用してください。読み取り専用 int8_t.
type: docs
weight: 690
url: /ja/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() メソッド


2Dチャートの棒と列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対しても適用されます。親シリーズ グループの対応するプロパティの投影であり、このプロパティは読み取り専用です。値を変更するには、[get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 読み書き可能プロパティを使用してください。読み取り専用 **int8_t**。

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## 備考


Overlap は棒と列の幅に対する重なりまたは間隔の度合いをパーセンテージで指定します:* -100%: 最大の間隔（棒が完全に分離しています）。* 0%: 棒が重なりも間隔もなく並んでいます。* 100%: 最大の重なり（棒が互いに完全に重なっています）。これはプロパティ [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) の投影です。

## 参照

* クラス [ChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)