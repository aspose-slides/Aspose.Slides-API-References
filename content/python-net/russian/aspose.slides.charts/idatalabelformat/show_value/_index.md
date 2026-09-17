---
title: show_value property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value свойство
Представляет поведение отображения процентного значения подписи данных указанной диаграммы. 
            True отображает процентное значение. False скрывает его.
            Чтение/запись **bool**.


### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это
            свойство получает или задает значение по умолчанию свойства ShowValue для новых подписей 
            данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowValue 
            для всех подписей данных в коллекции DataLabelCollection
            (т.е. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" приводит к тому, 
            что all DataLabels[i].ShowValue равно val).

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
* class [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)