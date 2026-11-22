---
title: secondary_categories property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories Eigenschaft
Gibt die sekundären Kategorien zurück, wenn [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft true ist.
            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).


### Hinweise

Wenn [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft false ist, dann gibt diese [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft None zurück und die Daten in [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft werden sowohl für primäre als auch für sekundäre Serien verwendet.
            Wenn [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft true ist, werden die Daten in dieser [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft für sekundäre Serien und die Daten in [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft für primäre Serien verwendet.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```


### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Klasse [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)