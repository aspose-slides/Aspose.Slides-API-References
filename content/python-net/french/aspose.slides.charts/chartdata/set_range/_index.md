---
title: set_range method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Définir la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données.
            Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.

```python
def set_range(self, formula):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| formula | **str** | La formule de plage de données des cellules. Par exemple: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula est None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Type de graphique non pris en charge |
| **RuntimeError(Proxy error(ArgumentException))** | la formule a un format incorrect. |

### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)