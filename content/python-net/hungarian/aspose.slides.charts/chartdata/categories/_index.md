---
title: categories property
second_title: Aspose.Slides a Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/categories/
weight: 70
---
## kategóriák tulajdonság
Lekéri az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat, ha a(z) [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis). Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).

### Megjegyzések

Ha a(z) [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis, akkor a(z) [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság None-t ad vissza, és az ebben a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonságban lévő adat mind az elsődleges, mind a másodlagos sorozathoz használható. Ha a(z) [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság igaz, akkor a(z) [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonságban lévő adat a másodlagos sorozathoz, az ebben a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonságban lévő adat pedig az elsődleges sorozathoz használható.

### Definíció:
```python
@property
def categories(self):
    ...
```

### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* osztály [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)