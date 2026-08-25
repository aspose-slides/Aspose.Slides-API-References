---
title: ChartDataWorkbook
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/chartdataworkbook/
---
## ChartDataWorkbook class

 Fournit un accès au classeur Excel intégré
 
### calculateFormulas {#calculateFormulas}

| Name | Description |
| --- | --- |
| calculateFormulas () | Calcule toutes les formules du classeur et met à jour les valeurs des cellules correspondantes. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | CellUnsupportedDataException | Les données de la cellule ne sont pas prises en charge. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear (int) | Efface toutes les valeurs des cellules sur la feuille |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Index de la feuille |

 **Returns:**
void


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, int, int) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories du graphique |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | Nom de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories du graphique |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories du graphique |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul. |
| cellName | String | Nom de la cellule. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String, Object) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories du graphique |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul. |
| cellName | String | Nom de la cellule. |
| value | Object | La valeur. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int, Object) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories du graphique |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |
| value | Object | La valeur. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCellCollection {#getCellCollection}

| Name | Description |
| --- | --- |
| getCellCollection (String, boolean) | Obtient l’ensemble des cellules. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | Formule Excel comme "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Si vrai, la méthode renvoie la collection sans les cellules masquées. |

 **Returns:**
[ChartCellCollection](../chartcellcollection)


---


### getWorksheets {#getWorksheets}

| Name | Description |
| --- | --- |
| getWorksheets () | Obtient une collection de feuilles de calcul. |

 **Returns:**
[ChartDataWorksheetCollection](../chartdataworksheetcollection)


---