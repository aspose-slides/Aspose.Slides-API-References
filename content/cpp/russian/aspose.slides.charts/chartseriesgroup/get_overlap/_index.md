---
title: get_Overlap()
second_title: Aspose.Slides для C++ справочник API
description: Указывает, насколько бары и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%).
type: docs
weight: 157
url: /ru/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() метод


Указывает, насколько бары и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Примечания


* -100%: Максимальное расстояние (бары полностью разделены).
* 0%: Бары размещаются рядом без перекрытия и без промежутков.
* 100%: Максимальное перекрытие (бары полностью перекрывают друг друга). Это свойство доступно для чтения и записи **int8_t**.



Следующий пример демонстрирует, как задать перекрытие для группы серий диаграммы и отобразить получившуюся диаграмму в форме: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Установить перекрытие на 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## См. также

* Класс [ChartSeriesGroup](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)