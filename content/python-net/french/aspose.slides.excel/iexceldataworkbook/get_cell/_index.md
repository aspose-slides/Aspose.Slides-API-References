---
title: get_cell method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et le nom de cellule de style Excel (par ex., "B2").

### Renvoie

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Indice basé à zéro de la feuille de calcul. |
| cell_name | **str** | La référence de cellule au format Excel (par ex., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule de style Excel (par ex., "B2").

### Renvoie

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | Le nom de la feuille de calcul. |
| cell_name | **str** | La référence de cellule au format Excel (par ex., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et les coordonnées de la cellule.

### Renvoie

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Indice basé à zéro de la feuille de calcul. |
| row | **int** | Indice de ligne basé à zéro de la cellule. |
| column | **int** | Indice de colonne basé à zéro de la cellule. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et les coordonnées de la cellule.

### Renvoie

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | Le nom de la feuille de calcul. |
| row | **int** | Indice de ligne basé à zéro de la cellule. |
| column | **int** | Indice de colonne basé à zéro de la cellule. |



### Voir aussi
* classe [`IExcelDataCell`](/slides/python-net/fr/aspose.slides.excel/iexceldatacell)
* classe [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook)
* module [`aspose.slides.excel`](/slides/python-net/fr/aspose.slides.excel)
* bibliothèque [`Aspose.Slides`](/slides/python-net)