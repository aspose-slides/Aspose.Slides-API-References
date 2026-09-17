---
title: show_bubble_size property
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size свойство
Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. 
            True отображает значение размера пузыря. False — скрыть.
            Чтение/запись **bool**.

### Примечания

Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых подписей данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех подписей данных в коллекции DataLabelCollection
            (т. е. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" приводит к тому, что все DataLabels[i].ShowBubbleSize равны val).

### Определение:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)