---
title: secondary_categories property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories свойство
Получает вторичные категории, если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) истинно.
            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).


### Примечания

Если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) ложно, то свойство [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) возвращает None и данные в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются как для основной, так и для вторичной серии.
Если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) истинно, то данные в свойстве [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) используются для вторичной серии, а данные в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются для основной серии.

### Определение:
```python
@property
def secondary_categories(self):
    ...
```


### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* класс [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)