---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API リファレンス
description: パイ・オブ・パイまたはバー・オブ・パイ チャートにおいて、どのデータポイントが第2のパイまたはバーに属するかを決定する方法を指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するもので、適切なグループ プロパティの投影です。そのためこのプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスします。get_ParentSeriesGroup()->get(set)_PieSplitBy() 読み取り/書き込み プロパティを使用して値を変更します。読み取り専用 PieSplitType。
type: docs
weight: 729
url: /ja/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() メソッド

このプロパティは、パイ・オブ・パイまたはバー・オブ・パイ チャートにおいて、どのデータポイントが第2のパイまたはバーに属するかを決定する方法を指定します。これはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスします。[get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 読み取り/書き込み プロパティを使用して値を変更します。読み取り専用 [PieSplitType](../../piesplittype/)。

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## 備考

1) これはプロパティ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() の投影です。 2) プロパティ値が [PieSplitType::Custom](../../piesplittype/) の場合、[get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) プロパティを使用してカスタム分割情報を定義できます。

## 参照

* 列挙体 [PieSplitType](../../piesplittype/)
* クラス [IChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)