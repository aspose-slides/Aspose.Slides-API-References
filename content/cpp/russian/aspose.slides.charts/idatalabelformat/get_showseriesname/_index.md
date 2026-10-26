---
title: get_ShowSeriesName()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение Boolean, указывающее поведение отображения имени серии для подписей данных на диаграмме. True — показать имя серии. False — скрыть. Read bool.
type: docs
weight: 170
url: /ru/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() метод

Возвращает значение Boolean, указывающее поведение отображения имени серии для подписи данных на диаграмме. True — показать имя серии. False — скрыть. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Примечания

Если родительский объект этого [DataLabelFormat](../../datalabelformat/) является [DataLabelCollection](../../datalabelcollection/) коллекцией подписей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowSeriesName для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowSeriesName для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" приводит к тому, что все DataLabels[i].ShowSeriesName равны val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)