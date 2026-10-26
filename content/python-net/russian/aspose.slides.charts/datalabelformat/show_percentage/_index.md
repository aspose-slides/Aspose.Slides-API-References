---
title: show_percentage property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage свойство
Represents a specified chart's data label percentage value display behavior. 
True отображает процентное значение. False — скрывает.
Чтение/запись **bool**.

### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подпечатей данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех подписей данных в коллекции DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" cause to all DataLabels[i].ShowPercentage is equal to val).

### Определение:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)