---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell свойство
Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. 
True отображает значение ячейки. False скрывает её. 
Чтение/запись **bool**.

### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписи данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых подп **** данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех подп **** в коллекции DataLabelCollection (т.е. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" приводит к всем DataLabels[i].ShowLabelValueFromCell = val).

### Определение:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)