---
title: get_Overlap()
second_title: Aspose.Slides for C++ API リファレンス
description: 2-D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズにも適用されます。親シリーズグループの該当プロパティの投影であり、このプロパティは読み取り専用です。値を変更するには、get_ParentSeriesGroup()->get(set)_Overlap() 読み書きプロパティを使用してください。読み取り専用 int8_t。
type: docs
weight: 690
url: /ja/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() メソッド

2-D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対しても適用されます。親シリーズグループの対応するプロパティの投影であり、このプロパティは読み取り専用です。値を変更するには、[get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() の読み書きプロパティを使用してください。読み取り専用 **int8_t**。

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## 備考


Overlap はバーと列の幅に対するパーセンテージで、重なりまたは間隔の程度を指定します:* -100%: 最大の間隔（バーは完全に分離しています）。* 0%: バーは重なりや間隔なしで横に並びます。* 100%: 最大の重なり（バーが完全に重なります）。これはプロパティ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() の投影です。

## 参照

* クラス [IChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)