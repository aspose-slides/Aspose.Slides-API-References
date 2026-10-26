---
title: categories property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories Eigenschaft
Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft false ist). Nur lesbar [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).

### Hinweise
Wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft false ist, dann gibt die [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) Eigenschaft None zurück und Daten in dieser [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft werden sowohl für primäre als auch für sekundäre Serien verwendet.
Wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft true ist, dann werden Daten in der [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) Eigenschaft für sekundäre Serien verwendet und Daten in dieser [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft für primäre Serien verwendet.

### Definition:
```python
@property
def categories(self):
    ...
```

### Siehe auch
* Klasse [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection)
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)