---
title: set_ShowSeriesName()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True, чтобы показать имя серии. False, чтобы скрыть. Запишите bool.
type: docs
weight: 183
url: /ru/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) метод

Устанавливает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True, чтобы показать имя серии. False, чтобы скрыть. Запишите **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## Примечания

Если родитель этого объекта [DataLabelFormat](../../datalabelformat/) является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т.е. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" приводит к тому, что все DataLabels[i].ShowSeriesName равно val). 

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)