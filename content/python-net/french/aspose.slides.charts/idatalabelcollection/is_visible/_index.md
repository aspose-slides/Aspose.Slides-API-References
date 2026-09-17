---
title: is_visible property
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible property
False signifie que l'étiquette de données n'est pas visible par défaut (et donc que tous
            les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false).
            Lecture seule **bool**.

### Remarks

Si l'étiquette de données est visible par défaut, vous pouvez la rendre cachée par défaut avec la méthode Hide().
            Mais si l'étiquette de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre l'étiquette de données « visible par défaut » en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état true.

### Definition:
```python
@property
def is_visible(self):
    ...
```

### See Also
* classe [`IDataLabelCollection`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)