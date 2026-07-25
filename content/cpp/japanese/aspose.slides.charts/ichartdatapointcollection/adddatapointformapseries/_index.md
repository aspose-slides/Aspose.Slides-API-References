---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータ ポイントを作成し、コレクションの末尾に追加します。チャートの種類がマップであるシリーズに適用できます。
type: docs
weight: 352
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。チャートの種類がマップであるシリーズに適用できます。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データ ポイント ColorValue |

### 戻り値

新しいデータ ポイント。

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)