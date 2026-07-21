---
title: set_ShowSeriesName()
second_title: Aspose.Slides для C++ API Reference
description: Устанавливает логическое значение, указывающее поведение отображения имени ряда для подписей данных на диаграмме. True, чтобы показать имя ряда. False, чтобы скрыть. Запишите bool.
type: docs
weight: 183
url: /ru/aspose.slides.charts/datalabelformat/set_showseriesname/
---
## DataLabelFormat::set_ShowSeriesName(bool) метод


Устанавливает логическое значение, указывающее поведение отображения имени ряда для подписей данных на диаграмме. True, чтобы показать имя ряда. False, чтобы скрыть. Запишите **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowSeriesName(bool value) override
```

## Примечания


Если родитель этого [DataLabelFormat](../) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установив это свойство со значением, вы также задаёте это значение свойству ShowSeriesName для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" приводит к тому, что у всех DataLabels[i].ShowSeriesName будет равно val). 



## См. также

* Класс [DataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)