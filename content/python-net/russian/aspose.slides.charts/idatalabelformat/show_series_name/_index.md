---
title: show_series_name property
second_title: Aspose.Slides для Python через .NET справка по API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name свойство
Возвращает или задает значение типа Boolean, указывающее поведение отображения имени серии для подписей данных на диаграмме. 
            True — показать имя серии. False — скрыть.
            Чтение/запись **bool**.


### Примечания

Если родитель объекта DataLabelFormat является коллекцией DataLabelCollection подписи данных, то это
            свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых подписи
            данных в коллекции DataLabelCollection.
            Задание этого свойства со значением также устанавливает это значение свойства ShowSeriesName
            для всех подписей данных в коллекции DataLabelCollection
            (например, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" приводит к
            тому, что все DataLabels[i].ShowSeriesName равны val).

### Определение:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)