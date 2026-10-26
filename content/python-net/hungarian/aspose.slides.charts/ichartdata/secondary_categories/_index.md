---
title: secondary_categories property
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories tulajdonság
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) property is true.
            Read-only [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).


### Megjegyzés

If [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) property is false then this [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) 
            property return None and data in [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) property is true then data in 
            this [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) property is used for secondary series and data 
            in [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) property is used for primary series.

### Definíció:
```python
@property
def secondary_categories(self):
    ...
```


### Lásd még
* osztály [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection)
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)