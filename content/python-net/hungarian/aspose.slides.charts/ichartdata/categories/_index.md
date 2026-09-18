---
title: categories property
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## kategóriák tulajdonság
Megkapja az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat is, ha a [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis). Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).


### Megjegyzés

Ha a [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis, akkor a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonság None értéket ad vissza, és a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot mind az elsődleges, mind a másodlagos sorozatokhoz használják. Ha a [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság igaz, akkor a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonságban lévő adatot a másodlagos sorozatokhoz, a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonságban lévő adatot pedig az elsődleges sorozatokhoz használják.

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