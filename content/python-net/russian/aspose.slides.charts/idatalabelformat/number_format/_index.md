---
title: number_format property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## свойство number_format
Представляет строку формата для объекта DataLabels.
            Чтение/запись **str**.


### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых меток данных в коллекции DataLabelCollection.
            Когда это свойство задаётся значением, это значение также задаётся для свойства NumberFormat для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" приводит к тому, что у всех DataLabels[i].NumberFormat будет значение val).

### Определение:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)