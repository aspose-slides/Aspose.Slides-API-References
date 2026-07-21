---
title: get_Overlap()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, насколько полосы и столбцы должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%).
type: docs
weight: 183
url: /ru/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() метод

Указывает, насколько полосы и столбцы должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Примечания

* -100%: Максимальный интервал (полосы полностью разделены).
* 0%: Полосы размещаются рядом без перекрытия и без зазора.
* 100%: Максимальное перекрытие (полосы полностью перекрывают друг друга). Это свойство доступно для чтения/записи **int8_t**.

Следующий пример демонстрирует, как установить перекрытие для группы серий диаграммы и отобразить полученную диаграмму в форме: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Установить перекрытие 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## См. также

* Класс [IChartSeriesGroup](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)