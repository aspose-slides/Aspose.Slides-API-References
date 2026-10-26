---
title: use_secondary_categories property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/use_secondary_categories/
weight: 150
---
## use_secondary_categories свойство
Если false, то [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) свойство возвращает None и данные 
            в [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) свойстве используется как для основной, так и для вторичной серии.
Если true, то данные в [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) свойстве используются для вторичной серии, а данные 
            в [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) свойстве используются для основной серии.
Чтение/запись **bool**.

### Определение:
```python
@property
def use_secondary_categories(self):
    ...

@use_secondary_categories.setter
def use_secondary_categories(self, value):
    ...
```

### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)