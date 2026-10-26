---
title: categories property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories свойство
Получает основные категории (или как основные, так и вторичные категории 
            если [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) property is false).
            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).

### Примечания

Если [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) property is false then [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) 
            свойство возвращает None и данные в этом [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) property используются как для основных 
            и вторичных рядов.
            Если [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) property is true then данные в [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) 
            property используется для вторичных рядов и данные в этом [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) property используются 
            для основных рядов.

### Определение:
```python
@property
def categories(self):
    ...
```

### Смотрите также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* класс [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)