---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された IChartSeries を検索し、Collection 全体での最初の出現のゼロベースインデックスを返します
type: docs
weight: 40
url: /ja/aspose.slides.charts/ichartseriescollection/indexof/
---
## IChartSeriesCollection::IndexOf(System::SharedPtr\<IChartSeries\>) メソッド


指定された [IChartSeries](../../ichartseries/) を検索し、Collection 全体内での最初の出現のゼロベースインデックスを返します。

```cpp
virtual int32_t Aspose::Slides::Charts::IChartSeriesCollection::IndexOf(System::SharedPtr<IChartSeries> value)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartSeries](../../ichartseries/)\> | [Chart](../../chart/) シリーズ値。 |

### 戻り値

見つかった場合は、CollectionBase 全体内で value の最初の出現のゼロベースインデックスを返します。見つからない場合は -1 を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeries](../../ichartseries/)
* クラス [IChartSeriesCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)