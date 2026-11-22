---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories tulajdonság
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság is true.
            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).

### Megjegyzések

If [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis, akkor ez a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) 
            tulajdonság None-értéket ad vissza, és a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot mind az elsődleges, 
            mind a másodlagos sorozatokhoz használják.
            Ha [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság igaz, akkor a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonságban lévő adatot a másodlagos sorozatokhoz, a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot pedig az elsődleges sorozatokhoz használják.

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