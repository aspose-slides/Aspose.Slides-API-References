---
title: show_leader_lines property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines свойство
Представляет поведение отображения направляющих линий подписей данных указанной диаграммы. 
            True отображает направляющие линии. False скрывает их.
            Чтение/запись **bool**.


### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых подписей данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" приводит к тому, что все DataLabels[i].ShowLeaderLines равны val).

### Определение:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)