---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された ChartSeries を検索し、Collection 全体で最初に出現する位置のゼロベースインデックスを返します
type: docs
weight: 79
url: /ja/aspose.slides.charts/chartseriescollection/indexof/
---
## ChartSeriesCollection::IndexOf(System::SharedPtr\<IChartSeries\>) メソッド

指定された [ChartSeries](../../chartseries/) を検索し、Collection全体内で最初に出現する位置のゼロベースインデックスを返します

```cpp
int32_t Aspose::Slides::Charts::ChartSeriesCollection::IndexOf(System::SharedPtr<IChartSeries> value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartSeries](../../ichartseries/)\> | [Chart](../../chart/) シリーズの値。 |

### 戻り値

value が CollectionBase 全体で最初に出現する位置のゼロベースインデックス（見つかった場合）。見つからない場合は -1。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeries](../../ichartseries/)
* クラス [ChartSeriesCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)