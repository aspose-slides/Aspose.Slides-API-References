---
title: Table
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/table/
---
## Classe Table

 Représente un tableau sur une diapositive.
 
### getColumns {#getColumns}

| Nom | Description |
| --- | --- |
| getColumns () | Renvoie la collection des colonnes. Read-only IColumnCollection. |

 **Renvoie :**
[ColumnCollection](../columncollection)


---


### getFillFormat {#getFillFormat}

| Nom | Description |
| --- | --- |
| getFillFormat () | Renvoie un objet TableFormat.FillFormat contenant le format de remplissage pour la Table. Read-only IFillFormat. |

 **Renvoie :**
[FillFormat](../fillformat)


---


### getFirstCol {#getFirstCol}

| Nom | Description |
| --- | --- |
| getFirstCol () | Détermine si la première colonne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
boolean


---


### getFirstRow {#getFirstRow}

| Nom | Description |
| --- | --- |
| getFirstRow () | Détermine si la première ligne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
boolean


---


### getHorizontalBanding {#getHorizontalBanding}

| Nom | Description |
| --- | --- |
| getHorizontalBanding () | Détermine si les lignes paires doivent être dessinées avec un format différent. Read/write boolean. |

 **Renvoie :**
boolean


---


### getLastCol {#getLastCol}

| Nom | Description |
| --- | --- |
| getLastCol () | Détermine si la dernière colonne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
boolean


---


### getLastRow {#getLastRow}

| Nom | Description |
| --- | --- |
| getLastRow () | Détermine si la dernière ligne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
boolean


---


### getRightToLeft {#getRightToLeft}

| Nom | Description |
| --- | --- |
| getRightToLeft () | Détermine si le tableau a un ordre de lecture de droite à gauche. Read-write boolean. |

 **Renvoie :**
boolean


---


### getRows {#getRows}

| Nom | Description |
| --- | --- |
| getRows () | Renvoie la collection des lignes. Read-only IRowCollection. |

 **Renvoie :**
[RowCollection](../rowcollection)


---


### getStylePreset {#getStylePreset}

| Nom | Description |
| --- | --- |
| getStylePreset () | Obtient ou définit le style de tableau intégré. Read/write TableStylePreset. |

 **Renvoie :**
int


---


### getTableFormat {#getTableFormat}

| Nom | Description |
| --- | --- |
| getTableFormat () | Renvoie l’objet TableFormat qui contient les propriétés de mise en forme pour ce tableau. Read-only ITableFormat. |

 **Renvoie :**
[TableFormat](../tableformat)


---


### getVerticalBanding {#getVerticalBanding}

| Nom | Description |
| --- | --- |
| getVerticalBanding () | Détermine si les colonnes paires doivent être dessinées avec un format différent. Read/write boolean. |

 **Renvoie :**
boolean


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int, int) | Renvoie la cellule aux index de colonne et de ligne spécifiés. Read-only Cell. |

 **Renvoie :**
[Cell](../cell)


---


### mergeCells {#mergeCells}

| Nom | Description |
| --- | --- |
| mergeCells ([Cell](../cell), [Cell](../cell), boolean) | Fusionne les cellules voisines. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| cell1 | [Cell](../cell) | Cellule à fusionner. |
| cell2 | [Cell](../cell) | Cellule à fusionner. |
| allowSplitting | boolean | Vrai pour autoriser la division des cellules. |

 **Renvoie :**
[Cell](../cell)


---


### setFirstCol {#setFirstCol}

| Nom | Description |
| --- | --- |
| setFirstCol (boolean) | Détermine si la première colonne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
void


---


### setFirstRow {#setFirstRow}

| Nom | Description |
| --- | --- |
| setFirstRow (boolean) | Détermine si la première ligne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
void


---


### setHorizontalBanding {#setHorizontalBanding}

| Nom | Description |
| --- | --- |
| setHorizontalBanding (boolean) | Détermine si les lignes paires doivent être dessinées avec un format différent. Read/write boolean. |

 **Renvoie :**
void


---


### setLastCol {#setLastCol}

| Nom | Description |
| --- | --- |
| setLastCol (boolean) | Détermine si la dernière colonne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
void


---


### setLastRow {#setLastRow}

| Nom | Description |
| --- | --- |
| setLastRow (boolean) | Détermine si la dernière ligne d’un tableau doit être dessinée avec un format spécial. Read/write boolean. |

 **Renvoie :**
void


---


### setRightToLeft {#setRightToLeft}

| Nom | Description |
| --- | --- |
| setRightToLeft (boolean) | Détermine si le tableau a un ordre de lecture de droite à gauche. Read-write boolean. |

 **Renvoie :**
void


---


### setStylePreset {#setStylePreset}

| Nom | Description |
| --- | --- |
| setStylePreset (int) | Obtient ou définit le style de tableau intégré. Read/write TableStylePreset. |

 **Renvoie :**
void


---


### setTextFormat {#setTextFormat}

| Nom | Description |
| --- | --- |
| setTextFormat ([PortionFormat](../portionformat)) | Définit les propriétés de format de portion définies pour toutes les portions des cellules du tableau. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../portionformat) | Objet IPortionFormat avec les propriétés nécessaires définies. |

 **Renvoie :**
void


---


### setTextFormat {#setTextFormat}

| Nom | Description |
| --- | --- |
| setTextFormat ([ParagraphFormat](../paragraphformat)) | Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules du tableau. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../paragraphformat) | Objet IParagraphFormat avec les propriétés nécessaires définies. |

 **Renvoie :**
void


---


### setTextFormat {#setTextFormat}

| Nom | Description |
| --- | --- |
| setTextFormat ([TextFrameFormat](../textframeformat)) | Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules du tableau. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../textframeformat) | Objet ITextFrameFormat avec les propriétés nécessaires définies. |

 **Renvoie :**
void


---


### setVerticalBanding {#setVerticalBanding}

| Nom | Description |
| --- | --- |
| setVerticalBanding (boolean) | Détermine si les colonnes paires doivent être dessinées avec un format différent. Read/write boolean. |

 **Renvoie :**
void


---