---
title: secondary_categories property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories Eigenschaft
Ruft die sekundären Kategorien ab, wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft true ist.
            Schreibgeschützt [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).


### Hinweise

Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft false ist, dann gibt diese [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft None zurück und die Daten in der [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft werden sowohl für die primäre als auch für die sekundäre Serie verwendet.
            Wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) Eigenschaft true ist, werden die Daten in dieser [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) Eigenschaft für die sekundäre Serie verwendet und die Daten in der [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) Eigenschaft für die primäre Serie verwendet.

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