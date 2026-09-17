---
title: is_visible property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible propriété
False signifie que l'étiquette de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont faux). Lecture seule **bool**.

### Remarques
Si l'étiquette de données est visible par défaut, vous pouvez la rendre cachée par défaut avec la méthode Hide(). Mais si l'étiquette de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre l'étiquette de données "visible by default" en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sur l'état vrai.

### Définition:
```python
@property
def is_visible(self):
    ...
```

### Voir aussi
* classe [`DataLabelCollection`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)