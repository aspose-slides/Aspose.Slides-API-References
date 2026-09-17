---
title: set_range method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Définit la plage de données du graphique. Series et catégories seront mises à jour en fonction de la nouvelle plage de données.
Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.

```python
def set_range(self, formula):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| formula | **str** | La formule de plage de données des cellules. Ex: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | la formule est None. |
| **RuntimeError(Proxy error(ArgumentException))** | la formule a un format incorrect. |

### Voir aussi
* classe [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)