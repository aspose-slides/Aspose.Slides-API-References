---
title: get_cell method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et son nom de cellule au format Excel (par exemple, "B2").

### Retour

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Index de la feuille de calcul basé sur zéro. |
| cell_name | **str** | La référence de cellule au format Excel (par exemple, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par exemple, "B2").

### Retour

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | Le nom de la feuille de calcul. |
| cell_name | **str** | La référence de cellule au format Excel (par exemple, "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et les coordonnées de la cellule.

### Retour

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Index de la feuille de calcul basé sur zéro. |
| row | **int** | Index de ligne de la cellule basé sur zéro. |
| column | **int** | Index de colonne de la cellule basé sur zéro. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et les coordonnées de la cellule.

### Retour

La cellule à l'emplacement spécifié.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | Le nom de la feuille de calcul. |
| row | **int** | Index de ligne de la cellule basé sur zéro. |
| column | **int** | Index de colonne de la cellule basé sur zéro. |



### Voir aussi
* classe [`ExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook)
* classe [`IExcelDataCell`](/slides/python-net/fr/aspose.slides.excel/iexceldatacell)
* module [`aspose.slides.excel`](/slides/python-net/fr/aspose.slides.excel)
* bibliothèque [`Aspose.Slides`](/slides/python-net)