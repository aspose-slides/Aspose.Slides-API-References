---
title: get_Format()
second_title: Aspose.Slides for C++ API リファレンス
description: データポイントレベルの書式設定プロパティを表します。IFormat を参照してください。
type: docs
weight: 1
url: /ja/aspose.slides.charts/chartdatapointlevel/get_format/
---
## ChartDataPointLevel::get_Format() メソッド


データポイントレベルの書式設定プロパティを表します。[IFormat](../../iformat/) を参照してください。

```cpp
System::SharedPtr<IFormat> Aspose::Slides::Charts::ChartDataPointLevel::get_Format() override
```

## 備考



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IFormat](../../iformat/)
* クラス [ChartDataPointLevel](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)