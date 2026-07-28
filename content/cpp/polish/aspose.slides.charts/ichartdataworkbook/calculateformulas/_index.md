---
title: CalculateFormulas()
second_title: Aspose.Slides dla C++ – Referencja API
description: Oblicza wszystkie formuły w skoroszycie i aktualizuje odpowiednie wartości komórek.
type: docs
weight: 14
url: /pl/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() metoda


Oblicza wszystkie formuły w skoroszycie i aktualizuje odpowiednie wartości komórek.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Uwagi



Przykład pokazuje, jak przypisać formułę do komórki i obliczyć wartość. Wartość komórki \"B4\" jest ustawiana na 5. 
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

## Zobacz także

* Klasa [IChartDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)