---
title: position property
second_title: Aspose.Slides для Python через .NET справка по API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## свойство position
Представляет позицию метки данных.
Чтение/запись [`LegendDataLabelPosition`](/slides/python-net/ru/aspose.slides.charts/legenddatalabelposition).

### Примечания

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Position для новых меток данных в коллекции DataLabelCollection.
            Представляет позицию для объектов DataLabel.
            Установка этого свойства со значением также задает это значение свойству Position для всех меток данных в коллекции DataLabelCollection
            (т. е. "DataLabels.DefaultDataLabelFormat.Position = val;" приводит к тому, что
            всех DataLabels[i].Position будет равно val).

### Определение:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* перечисление [`LegendDataLabelPosition`](/slides/python-net/ru/aspose.slides.charts/legenddatalabelposition)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)