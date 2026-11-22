---
title: secondary_categories property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories Eigenschaft
Gibt die sekundären Kategorien zurück, wenn [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft true ist.
            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection).

### Bemerkungen

Wenn [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft false ist, dann diese [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) 
            Eigenschaft gibt None zurück und die Daten in [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft werden sowohl für die primäre 
            und sekundäre Serien.

Wenn [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) Eigenschaft true ist, dann werden Daten in 
            dieser [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) Eigenschaft für sekundäre Serien verwendet und Daten 
            in [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) Eigenschaft für primäre Serien verwendet.

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