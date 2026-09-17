---
title: show_bubble_size property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size свойство
Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. 
            True отображает значение размера пузыря. False скрывает.
            Чтение/запись **bool**.

### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection меток данных, то это
            свойство получает или задаёт значение по умолчанию свойства ShowBubbleSize для новых меток 
            данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задаёт это значение свойству ShowBubbleSize 
            для всех меток данных в коллекции DataLabelCollection
            (например, "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" приводит к тому, 
            что все DataLabels[i].ShowBubbleSize равно val).

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
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)