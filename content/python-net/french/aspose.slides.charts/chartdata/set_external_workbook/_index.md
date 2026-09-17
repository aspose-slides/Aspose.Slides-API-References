---
title: set_external_workbook method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Définit le classeur externe comme source de données pour le graphique. Les données du graphique seront mises à jour à partir du classeur cible.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Chemin vers le classeur cible |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Le classeur externe n'est pas disponible ou ne peut pas être chargé. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Définit le classeur externe comme source de données pour le graphique.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Chemin vers le classeur cible |
| update_chart_data | **bool** | Si la valeur est false, seul le chemin du classeur sera mis à jour. <br/><br/>             Les données du graphique ne seront pas chargées ni mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible.<br/><br/>             Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Le classeur externe n'est pas disponible ou ne peut pas être chargé. |



### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)