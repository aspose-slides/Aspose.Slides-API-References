---
title: categories property
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## kategóriák tulajdonság
Visszaadja az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat, ha [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis). Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).

### Megjegyzés

Ha [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis, akkor [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonság None-t ad vissza, és az ebben a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot használják mind az elsődleges, mind a másodlagos sorozathoz. Ha [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság igaz, akkor [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonságban lévő adatot használják a másodlagos sorozathoz, és az ebben a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot használják az elsődleges sorozathoz.

### Definíció:
```python
@property
def categories(self):
    ...
```

### Lásd még
* osztály [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection)
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)