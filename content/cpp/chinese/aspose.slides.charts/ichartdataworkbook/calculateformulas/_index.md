---
title: CalculateFormulas()
second_title: Aspose.Slides C++ API 参考
description: 计算工作簿中的所有公式并更新相应单元格的值。
type: docs
weight: 14
url: /zh/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() 方法

计算工作簿中的所有公式并更新相应单元格的值。

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## 备注



示例展示了如何将公式分配给单元格并计算其数值。\"B4\" 单元格的值被设置为 5。 
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

## 另请参阅

* 类 [IChartDataWorkbook](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)