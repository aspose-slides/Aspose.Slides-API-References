---
title: show_category_name property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name свойство
Представляет поведение отображения имени категории подписи данных заданной диаграммы.
True — отображать имя категории для подписей данных на диаграмме. False — скрывать.
Чтение/запись **bool**.


### Примечания

Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых подписей данных в коллекции DataLabelCollection.
Установка этого свойства со значением также задает это значение свойству ShowCategoryName для всех подписей данных в коллекции DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" приводит к тому, что у всех DataLabels[i].ShowCategoryName будет значение val).

### Определение:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### См. также
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)