---
title: CalculateFormulas()
second_title: Aspose.Slides for C++ API referencia
description: Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellák értékeit.
type: docs
weight: 53
url: /hu/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metódus


Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellák értékeit.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Megjegyzés



Példa mutatja, hogyan lehet képletet hozzárendelni a cellához, és hogyan számítható ki az érték. A \"B4\" cella értéke 5-re lesz beállítva. 
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

## Lásd még

* Osztály [ChartDataWorkbook](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)