---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的資料點並將其加入集合的末端。適用於圖表類型為 Map 的系列。
type: docs
weight: 352
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) 方法


建立新的資料點並將其加入集合的末端。適用於圖表類型為 Map 的系列。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點 ColorValue |

### 回傳值

新的資料點。

## 備註




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## 相關參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)