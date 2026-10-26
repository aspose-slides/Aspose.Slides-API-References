---
title: position property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## свойство position
Представляет значение свойства position подписи данных.
Чтение/запись [`LegendDataLabelPosition`](/slides/python-net/ru/aspose.slides.charts/legenddatalabelposition).

### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение свойства Position по умолчанию для новых подписей данных в коллекции DataLabelCollection.
Представляет позицию для объектов DataLabel.
Установка этого свойства со значением также устанавливает это значение в свойство Position для всех подписей данных в коллекции DataLabelCollection
(например, "DataLabels.DefaultDataLabelFormat.Position = val;" приводит к тому, что все DataLabels[i].Position равны val).

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
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* перечисление [`LegendDataLabelPosition`](/slides/python-net/ru/aspose.slides.charts/legenddatalabelposition)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)