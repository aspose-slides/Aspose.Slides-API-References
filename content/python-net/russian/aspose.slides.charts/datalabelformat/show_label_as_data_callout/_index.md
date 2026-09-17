---
title: show_label_as_data_callout property
second_title: Aspose.Slides для Python через .NET справка по API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout свойство
Определяет, будет ли метка данных указанного графика отображаться как выноска данных или как метка данных.
            
            Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause to 
            all DataLabels[i].ShowLabelAsDataCallout is equal to val).

### Определение:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```


### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)