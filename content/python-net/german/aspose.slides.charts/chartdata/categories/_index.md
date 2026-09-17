---
title: categories property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/categories/
weight: 70
---
## Kategorien-Eigenschaft
Liefert die primären Kategorien (oder sowohl primäre als auch sekundäre Kategorien, wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft falsch ist). Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).

### Bemerkungen

Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft falsch ist, dann gibt die [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft None zurück und die Daten in dieser [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft werden sowohl für die primäre als auch für die sekundäre Serie verwendet. Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft wahr ist, dann werden die Daten in der [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft für die sekundäre Serie verwendet und die Daten in dieser [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft für die primäre Serie verwendet.

### Definition:
```python
@property
def categories(self):
    ...
```

### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Klasse [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)