---
title: secondary_categories property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories egenskap
Hämtar de sekundära kategorierna om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är sann.
            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection).


### Anmärkningar

Om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är falsk då denna [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) 
            egenskap returnerar None och data i [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskap används både för primära 
            och sekundära serier.
Om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är sann så används data i 
            denna [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) egenskap för sekundära serier och data 
            i [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskap används för primära serier.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```


### Se också
* klass [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)