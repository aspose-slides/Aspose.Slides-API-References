---
title: CalculateFormulas()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk.
type: docs
weight: 53
url: /cs/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metoda


Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Poznámky



Příklad ukazuje, jak přiřadit vzorec buňce a vypočítat hodnotu. Hodnota buňky \"B4\" je nastavena na 5. 
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

## Viz také

* Třída [ChartDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)