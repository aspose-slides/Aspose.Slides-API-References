---
title: show_legend_key property
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key свойство
Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. 
            True, если ключ легенды подписи данных видим.
            Чтение/запись **bool**.

### Примечания

Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задает значение по умолчанию свойства ShowLegendKey для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" приводит к тому, что у всех DataLabels[i].ShowLegendKey будет значение val).

### Определение:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)