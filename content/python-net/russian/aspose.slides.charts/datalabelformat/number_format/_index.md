---
title: number_format property
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format свойство
Represents the format string for the DataLabels object.
Read/write **str**.

### Примечания
Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых меток данных в коллекции DataLabelCollection.  
Когда это свойство задаётся значением, это значение также устанавливается для свойства NumberFormat всех меток данных в коллекции DataLabelCollection (т.е. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" приводит к тому, что все DataLabels[i].NumberFormat становятся равными val).

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
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)