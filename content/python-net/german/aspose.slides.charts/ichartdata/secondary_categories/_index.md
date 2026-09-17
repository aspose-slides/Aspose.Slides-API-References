---
title: secondary_categories property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories Eigenschaft
Ruft die sekundären Kategorien ab, wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft true ist.
Nur lesbar [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).


### Hinweise

Wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft false ist, dann gibt diese [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) Eigenschaft None zurück und Daten in der [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft werden sowohl für die primäre als auch für die sekundäre Serie verwendet.
Wenn die [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft true ist, dann werden Daten in dieser [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) Eigenschaft für die sekundäre Serie verwendet und Daten in der [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft für die primäre Serie verwendet.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```


### Siehe auch
* Klasse [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection)
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)