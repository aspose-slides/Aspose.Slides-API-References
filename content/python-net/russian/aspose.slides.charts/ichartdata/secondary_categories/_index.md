---
title: secondary_categories property
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories свойство
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) свойство is true.
Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection).

### Примечания

Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) ложно, то это свойство [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) возвращает None, а данные в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются как для первичной, так и для вторичной серии.
Если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) истинно, то данные в этом свойстве [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) используются для вторичной серии, а данные в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются для первичной серии.

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