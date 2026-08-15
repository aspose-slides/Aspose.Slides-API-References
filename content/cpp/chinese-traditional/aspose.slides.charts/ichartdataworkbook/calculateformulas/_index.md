---
title: CalculateFormulas()
second_title: Aspose.Slides for C++ API 參考
description: 計算工作簿中的所有公式並更新相應儲存格的值。
type: docs
weight: 14
url: /zh-hant/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() 方法


計算工作簿中的所有公式並更新相應儲存格的值。

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## 備註



範例說明如何將公式指派給儲存格並計算其值。\"B4\" 儲存格的值被設為 5。 
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

## 另見

* 類別 [IChartDataWorkbook](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)