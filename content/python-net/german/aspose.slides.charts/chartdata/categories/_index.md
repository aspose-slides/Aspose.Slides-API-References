---
title: categories property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/categories/
weight: 80
---
## Kategorien Eigenschaft
Ruft die Primärkategorien ab (oder sowohl Primär- als auch Sekundärkategorien, wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft false ist). Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).

### Anmerkungen
Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft false ist, gibt die [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft None zurück und die Daten in dieser [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft werden sowohl für die Primär- als auch für die Sekundärserie verwendet. Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft true ist, werden die Daten in der [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft für die Sekundärserie verwendet und die Daten in dieser [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft für die Primärserie verwendet.

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