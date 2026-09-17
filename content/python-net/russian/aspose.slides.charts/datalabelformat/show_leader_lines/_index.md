---
title: show_leader_lines property
second_title: Aspose.Slides для Python через .NET API Справка
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines свойство
Представляет поведение отображения линий-указателей подписи данных заданной диаграммы. True отображает линии-указатели. False скрывает их. Чтение/запись **bool**.

### Примечания
Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это
            свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых подпесей
            данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству ShowLeaderLines
            для всех подпесей данных в коллекции DataLabelCollection
            (т. е. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" приводит к тому,
            что все DataLabels[i].ShowLeaderLines равны val).

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
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)