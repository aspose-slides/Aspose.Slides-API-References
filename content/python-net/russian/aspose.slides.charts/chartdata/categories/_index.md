---
title: categories property
second_title: Aspose.Slides для Python через .NET API Справка
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/categories/
weight: 80
---
## свойство categories
Получает основные категории (или как основные, так и вторичные категории, если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) равно false). Только чтение [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).

### Примечания

Если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) равно false, то свойство [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) возвращает None и данные в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются как для первичных, так и для вторичных рядов. Если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) равно true, то данные в свойстве [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) используются для вторичных рядов, а данные в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются для первичных рядов.

### Определение:
```python
@property
def categories(self):
    ...
```

### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* класс [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)