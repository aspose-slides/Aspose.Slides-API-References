---
title: secondary_categories property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories egenskap
Hämtar de sekundära kategorierna om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är sann.
            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection).


### Anmärkningar

Om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är falsk returnerar denna [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) 
            egenskap return None och data i [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) egenskap används både för primära 
            och sekundära serier.
Om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är sann används data i 
            denna [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) egenskap används för sekundära serier och data 
            i [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) egenskap används för primära serier.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```


### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* klass [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)