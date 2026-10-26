---
title: ChartCategory
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/chartcategory/
---
## ChartCategory classe

 Représente les catégories de graphique.
 
### getAsCell {#getAsCell}

| Nom | Description |
| --- | --- |
| getAsCell () | Renvoie ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l'objet IChartDataCell utilisé pour le niveau "0". Lecture/écriture IChartDataCell. |

 **Retour:**
[ChartDataCell](../chartdatacell)


---


### getAsLiteral {#getAsLiteral}

| Nom | Description |
| --- | --- |
| getAsLiteral () | Renvoie ou définit l'objet AsLiteral. Lecture/écriture Object. |

 **Retour:**
Object


---


### getGroupingLevels {#getGroupingLevels}

| Nom | Description |
| --- | --- |
| getGroupingLevels () | Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique. Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement. L'indexation des niveaux de regroupement commence à zéro. Lecture seule IChartCategoryLevelsManager. |

 **Retour:**
[ChartCategoryLevelsManager](../chartcategorylevelsmanager)


---


### getUseCell {#getUseCell}

| Nom | Description |
| --- | --- |
| getUseCell () | Si true alors la propriété AsCell est effective. En d'autres termes, la feuille de calcul est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux). Si false alors la propriété AsLiteral est effective. En d'autres termes, la feuille de calcul n'est PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Lecture seule boolean. Pour modifier la valeur de cette propriété (pour toutes les catégories de la collection) définissez la nouvelle valeur sur la propriété ChartCategoryCollection.UseCells. |

 **Retour:**
boolean


---


### getValue {#getValue}

| Nom | Description |
| --- | --- |
| getValue () | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object. |

 **Retour:**
Object


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove () | Supprime la catégorie du graphique. |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Levée si la catégorie a déjà été supprimée du graphique. |


---


### setAsCell {#setAsCell}

| Nom | Description |
| --- | --- |
| setAsCell ([ChartDataCell](../chartdatacell)) | Renvoie ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l'objet IChartDataCell utilisé pour le niveau "0". Lecture/écriture IChartDataCell. |

 **Retour:**
void


---


### setAsLiteral {#setAsLiteral}

| Nom | Description |
| --- | --- |
| setAsLiteral (Object) | Renvoie ou définit l'objet AsLiteral. Lecture/écriture Object. |

 **Retour:**
void


---


### setValue {#setValue}

| Nom | Description |
| --- | --- |
| setValue (Object) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object. |

 **Retour:**
void


---