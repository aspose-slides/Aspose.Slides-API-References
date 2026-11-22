---
title: categories property
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/categories/
weight: 80
---
## kategóriák tulajdonsága
A fő kategóriákat (vagy a fő és másodlagos kategóriákat is, ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis) adja vissza.  
Csak-olvasású [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection).

### Megjegyzések

Ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság None-t ad vissza, és a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság adatai a fő és a másodlagos sorozathoz is felhasználásra kerülnek.  
Ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság igaz, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság adatai a másodlagos sorozathoz, a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság adatai pedig a fő sorozathoz kerülnek felhasználásra.

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