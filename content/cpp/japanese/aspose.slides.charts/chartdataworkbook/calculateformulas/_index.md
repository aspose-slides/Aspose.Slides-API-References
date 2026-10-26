---
title: CalculateFormulas()
second_title: Aspose.Slides for C++ API リファレンス
description: ワークブック内のすべての数式を計算し、対応するセルの値を更新します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() メソッド


ワークブック内のすべての数式を計算し、対応するセルの値を更新します。

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## 備考



この例は、セルに数式を割り当てて値を計算する方法を示しています。\"B4\" セルの値は 5 に設定されます。 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## 参照

* クラス [ChartDataWorkbook](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)