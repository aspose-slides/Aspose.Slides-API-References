---
title: CalculateFormulas()
second_title: Ссылка на API Aspose.Slides для C++
description: Вычисляет все формулы в рабочей книге и обновляет соответствующие значения ячеек.
type: docs
weight: 14
url: /ru/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() метод

Вычисляет все формулы в рабочей книге и обновляет соответствующие значения ячеек.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Примечания

Пример показывает, как присвоить формулу ячейке и вычислить значение. Значение ячейки "B4" устанавливается в 5. 
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

## См. также

* Класс [IChartDataWorkbook](../)
* Пространство имен [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)