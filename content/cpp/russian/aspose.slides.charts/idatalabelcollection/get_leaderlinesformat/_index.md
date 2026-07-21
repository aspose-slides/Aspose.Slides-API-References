---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides для C++ справочник API
description: Представляет формат линий-выносов подписей данных. Только для чтения IChartLinesFormat.
type: docs
weight: 14
url: /ru/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() метод


Представляет формат линий-выносов подписей данных. Только для чтения [IChartLinesFormat](../../ichartlinesformat/).

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## Примечания


Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartLinesFormat](../../ichartlinesformat/)
* Класс [IDataLabelCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)