---
title: show_category_name property
second_title: Aspose.Slides для Python через .NET Справка API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name свойство
Представляет поведение отображения названия категории подписи данных заданной диаграммы.
True — отображать название категории для подписей данных на диаграмме. False — скрыть.
Чтение/запись **bool**.

### Примечания

Если родитель объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowCategoryName для новых подписей данных в коллекции DataLabelCollection.
Установка этого свойства со значением также задаёт это значение свойству ShowCategoryName для всех подписей данных в коллекции DataLabelCollection
(например, "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" приводит к тому, что у всех DataLabels[i].ShowCategoryName будет значение val).

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
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)