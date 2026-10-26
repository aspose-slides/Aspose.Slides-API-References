---
title: categories property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories свойство
Возвращает основные категории (или как основные, так и вторичные категории 
            если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) ложно).
            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).

### Замечания

Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) ложно, то свойство [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) возвращает None, а данные в этом свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются как для основных, так и для вторичных рядов.
            Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) истинно, то данные в свойстве [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) используются для вторичных рядов, а данные в этом свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются для основных рядов.

### Определение:
```python
@property
def categories(self):
    ...
```

### См. также
* класс [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection)
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)