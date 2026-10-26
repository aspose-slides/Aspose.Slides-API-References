---
title: ChartCellCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/chartcellcollection/
---
## ChartCellCollection classe

 Représente une collection de cellules avec des données.
 
### add {#add}

| Nom | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | Ajoute une nouvelle cellule à la collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | Nouvelle cellule à ajouter. |

 **Retour:**
void


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (Object) | Crée ChartDataCell à partir de la valeur spécifiée et l’ajoute à la collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | Object | La valeur. Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez ChartDataWorkbook pour ajouter ou modifier des valeurs Cell, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680 |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | si la limite est dépassée |


---


### getCellsAddress {#getCellsAddress}

| Nom | Description |
| --- | --- |
| getCellsAddress () | Renvoie l’adresse de l’ensemble de cellules dans le classeur. |

 **Retour:**
String


---


### getConcatenatedValuesFromCells {#getConcatenatedValuesFromCells}

| Nom | Description |
| --- | --- |
| getConcatenatedValuesFromCells () | Chaîne de concaténation provenant de toutes les valeurs de chaîne des cellules. |

 **Retour:**
String


---


### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Obtient le nombre de cellules dans la collection. int en lecture seule. |

 **Retour:**
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie une cellule (IChartDataCell) par indice. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice d’une cellule. |

 **Retour:**
[ChartDataCell](../chartdatacell)


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour:**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l’ensemble de la collection. |

 **Retour:**



---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime une cellule de la collection par indice. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de la cellule à supprimer. |

 **Retour:**
void


---