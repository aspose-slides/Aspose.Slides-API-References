---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API リファレンス
description: パイ・オブ・パイまたはバー・オブ・パイチャートにおいて、どのデータポイントが第2のパイまたはバーに属するかを決定する方法を指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズのプロパティであり、適切なグループプロパティの投影です。そのため、このプロパティは読み取り専用です。親シリーズグループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには get_ParentSeriesGroup()->get(set)_PieSplitBy() 読み書きプロパティを使用します。読み取り専用 PieSplitType。
type: docs
weight: 755
url: /ja/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() メソッド

パイ・オブ・パイまたはバー・オブ・パイチャートにおいて、どのデータポイントが第2のパイまたはバーに属するかを決定する方法を指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズのプロパティであり、適切なグループプロパティの投影です。したがって、このプロパティは読み取り専用です。親シリーズグループにアクセスするには ParentSeriesGroup プロパティを使用します。[get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 読み書き プロパティを使用して値を変更します。読み取り専用 [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## 備考

1) これはプロパティ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() の投影です。 2) プロパティの値が [PieSplitType::Custom](../../piesplittype/) の場合、[get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) プロパティでカスタム分割情報を定義できます。

## 参照

* Enum [PieSplitType](../../piesplittype/)
* クラス [ChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)