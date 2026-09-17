---
title: show_value property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value свойство
Представляет поведение отображения процентного значения подписи данных указанной диаграммы. 
True отображает процентное значение. False скрывает его.
Чтение/запись **bool**.


### Примечания

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowValue для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает это значение свойству ShowValue для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.ShowValue = val;" приводит к тому, что у всех DataLabels[i].ShowValue будет равно val).

### Определение:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)