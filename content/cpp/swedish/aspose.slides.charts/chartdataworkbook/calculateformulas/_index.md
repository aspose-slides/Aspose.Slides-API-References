---
title: CalculateFormulas()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden.
type: docs
weight: 53
url: /sv/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metod


Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Anmärkningar



Exemplet visar hur man tilldelar en formel till cellen och beräknar ett värde. Värdet på cellen \"B4\" sätts till 5. 
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

## Se också

* Klass [ChartDataWorkbook](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)