---
title: secondary_categories property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories tulajdonság
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) property is true.
            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).


### Megjegyzések

Ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis, akkor ez a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) 
            tulajdonság None-t ad vissza, és a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság adatait mind az elsődleges 
            és a másodlagos sorozathoz.
            Ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság igaz, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) 
            tulajdonság a másodlagos sorozathoz használják, és az adat 
            a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság az elsődleges sorozathoz használják.

### Definíció:
```python
@property
def secondary_categories(self):
    ...
```


### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* osztály [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)