---
title: show_series_name property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name свойство
Возвращает или задает значение типа Boolean, указывающее поведение отображения имени серии для подписей данных на диаграмме.  
True — показывать имя серии. False — скрывать.  
Чтение/запись **bool**.

### Примечания

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых подписей данных в коллекции DataLabelCollection.  
Установка этого свойства также задает значение свойства ShowSeriesName для всех подписей данных в коллекции DataLabelCollection  
(т.е. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" приводит к тому, что все DataLabels[i].ShowSeriesName равны val).

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
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)