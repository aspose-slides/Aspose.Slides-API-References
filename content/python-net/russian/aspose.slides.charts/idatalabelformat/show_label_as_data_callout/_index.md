---
title: show_label_as_data_callout property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout свойство
Определяет, будет ли метка данных указанной диаграммы отображаться как примечание к данным или как метка данных.

            Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или устанавливает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection
            (т.е. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" приводит к тому, что все DataLabels[i].ShowLabelAsDataCallout равны val).

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
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)