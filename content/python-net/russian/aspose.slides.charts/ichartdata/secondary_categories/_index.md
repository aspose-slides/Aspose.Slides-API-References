---
title: secondary_categories property
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories свойство
Получает вторичные категории, если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) истинно.
Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).

### Примечания

Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) ложно, то это [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) 
            свойство возвращает None, а данные в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются как для основной 
            и вторичной серии.
Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) истинно, то данные в 
            этом [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) свойстве используются для вторичной серии и данные 
            в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются для основной серии.

### Определение:
```python
@property
def secondary_categories(self):
    ...
```

### См. также
* класс [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection)
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)