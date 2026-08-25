---
title: MathMatrix
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/mathmatrix/
---
## MathMatrix classe

 Spécifie l’objet Matrix, composé d’éléments enfants disposés en une ou plusieurs lignes et colonnes.  
 Il est important de noter que les matrices n’ont pas de délimiteurs intégrés.  
 Pour placer la matrice entre crochets, vous devez utiliser l’objet délimiteur (IMathDelimiter).  
 Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.
 
### MathMatrix {#MathMatrix}

| Nom | Description |
| --- | --- |
| MathMatrix(int, int) | Initialise une nouvelle instance de la classe MathMatrix. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| rowCount | int | nombre de lignes |
| columnCount | int | nombre de colonnes |

 **Retour :**
MathMatrix


---


### deleteColumn {#deleteColumn}

| Nom | Description |
| --- | --- |
| deleteColumn (int) | Supprime la colonne spécifiée |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | L’index basé sur zéro de la colonne à supprimer. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Si columnIndex est inférieur à zéro ou supérieur ou égal à ColumnCount |


---


### deleteRow {#deleteRow}

| Nom | Description |
| --- | --- |
| deleteRow (int) | Supprime la ligne spécifiée |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| rowIndex | int | L’index basé sur zéro de la ligne à supprimer. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Si rowIndex est inférieur à zéro ou supérieur ou égal à RowCount |


---


### getBaseJustification {#getBaseJustification}

| Nom | Description |
| --- | --- |
| getBaseJustification () | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Défaut : Center |

 **Retour :**
int


---


### getChildren {#getChildren}

| Nom | Description |
| --- | --- |
| getChildren () | Obtient les éléments enfants |

 **Retour :**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)


---


### getColumnAlignment {#getColumnAlignment}

| Nom | Description |
| --- | --- |
| getColumnAlignment (int) | Obtient l’alignement horizontal de la colonne spécifiée |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |

 **Retour :**
int


---


### getColumnCount {#getColumnCount}

| Nom | Description |
| --- | --- |
| getColumnCount () | Nombre de colonnes dans la matrice |

 **Retour :**
int


---


### getColumnGap {#getColumnGap}

| Nom | Description |
| --- | --- |
| getColumnGap () | Valeur de l’espacement horizontal entre les colonnes d’une matrice ; si ColumnGapRule vaut 3 (« Exactly »), l’unité est interprétée en twips (1/20 de point). Si ColumnGapRule vaut 4 (« Multiple »), l’unité correspond au nombre d’incréments de 0,5 em. Dans les autres cas, ignoré. Défaut : 0 |

 **Retour :**
long


---


### getColumnGapRule {#getColumnGapRule}

| Nom | Description |
| --- | --- |
| getColumnGapRule () | Type d’espacement horizontal entre les colonnes d’une matrice ; les unités peuvent être des ems ou des points (stockés en twips). Défaut : SingleSpacingGap (0) |

 **Retour :**
int


---


### getHidePlaceholders {#getHidePlaceholders}

| Nom | Description |
| --- | --- |
| getHidePlaceholders () | Masque les espaces réservés pour les éléments vides de la matrice. Défaut : false |

 **Retour :**
boolean


---


### getMinColumnWidth {#getMinColumnWidth}

| Nom | Description |
| --- | --- |
| getMinColumnWidth () | Largeur minimale de colonne en twips (1/20 de point). L’espacement de la gouttière (aussi appelé « Column Gap » ou « Gap Width ») est ajouté à MinColumnWidth pour déterminer l’espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Défaut : 0. |

 **Retour :**
long


---


### getRowCount {#getRowCount}

| Nom | Description |
| --- | --- |
| getRowCount () | Nombre de lignes dans la matrice |

 **Retour :**
int


---


### getRowGap {#getRowGap}

| Nom | Description |
| --- | --- |
| getRowGap () | Valeur de l’espacement vertical entre les lignes d’une matrice ; si RowGapRule vaut 3 (« Exactly »), l’unité est interprétée en twips (1/20 de point). Si RowGapRule vaut 4 (« Multiple »), l’unité correspond à des demi-lignes. Défaut : 0 |

 **Retour :**
long


---


### getRowGapRule {#getRowGapRule}

| Nom | Description |
| --- | --- |
| getRowGapRule () | Type d’espacement vertical entre les lignes d’une matrice ; les unités peuvent être des lignes ou des points (stockés en twips). Défaut : SingleSpacingGap (0) |

 **Retour :**
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int, int) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)


---


### insertColumnAfter {#insertColumnAfter}

| Nom | Description |
| --- | --- |
| insertColumnAfter (int) | Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de la colonne après laquelle insérer une nouvelle colonne |

 **Retour :**
void


---


### insertColumnBefore {#insertColumnBefore}

| Nom | Description |
| --- | --- |
| insertColumnBefore (int) | Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de la colonne avant laquelle insérer une nouvelle colonne |

 **Retour :**
void


---


### insertRowAfter {#insertRowAfter}

| Nom | Description |
| --- | --- |
| insertRowAfter (int) | Insère une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index de la ligne après laquelle insérer une nouvelle ligne |

 **Retour :**
void


---


### insertRowBefore {#insertRowBefore}

| Nom | Description |
| --- | --- |
| insertRowBefore (int) | Insère une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index de la ligne avant laquelle insérer une nouvelle ligne |

 **Retour :**
void


---


### setBaseJustification {#setBaseJustification}

| Nom | Description |
| --- | --- |
| setBaseJustification (int) | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Défaut : Center |

 **Retour :**
void


---


### setColumnAlignment {#setColumnAlignment}

| Nom | Description |
| --- | --- |
| setColumnAlignment (int, int) | Définit l’alignement horizontal de la colonne spécifiée |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |
| val | int | Nouvelle valeur de l’alignement horizontal de la colonne spécifiée |

 **Retour :**
void


---


### setColumnGap {#setColumnGap}

| Nom | Description |
| --- | --- |
| setColumnGap (long) | Valeur de l’espacement horizontal entre les colonnes d’une matrice ; si ColumnGapRule vaut 3 (« Exactly »), l’unité est interprétée en twips (1/20 de point). Si ColumnGapRule vaut 4 (« Multiple »), l’unité correspond au nombre d’incréments de 0,5 em. Dans les autres cas, ignoré. Défaut : 0 |

 **Retour :**
void


---


### setColumnGapRule {#setColumnGapRule}

| Nom | Description |
| --- | --- |
| setColumnGapRule (int) | Type d’espacement horizontal entre les colonnes d’une matrice ; les unités peuvent être des ems ou des points (stockés en twips). Défaut : SingleSpacingGap (0) |

 **Retour :**
void


---


### setColumnsAlignment {#setColumnsAlignment}

| Nom | Description |
| --- | --- |
| setColumnsAlignment (int, long, int) | Définit l’alignement horizontal des colonnes spécifiées |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index basé sur zéro de la première colonne dont on définit l’alignement |
| columnsCount | long | Nombre de colonnes pour lesquelles définir l’alignement |
| val | int | Nouvelle valeur de l’alignement horizontal des colonnes spécifiées |

 **Retour :**
void


---


### setHidePlaceholders {#setHidePlaceholders}

| Nom | Description |
| --- | --- |
| setHidePlaceholders (boolean) | Masque les espaces réservés pour les éléments vides de la matrice. Défaut : false |

 **Retour :**
void


---


### setMinColumnWidth {#setMinColumnWidth}

| Nom | Description |
| --- | --- |
| setMinColumnWidth (long) | Largeur minimale de colonne en twips (1/20 de point). L’espacement de la gouttière (aussi appelé « Column Gap » ou « Gap Width ») est ajouté à MinColumnWidth pour déterminer l’espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Défaut : 0. |

 **Retour :**
void


---


### setRowGap {#setRowGap}

| Nom | Description |
| --- | --- |
| setRowGap (long) | Valeur de l’espacement vertical entre les lignes d’une matrice ; si RowGapRule vaut 3 (« Exactly »), l’unité est interprétée en twips (1/20 de point). Si RowGapRule vaut 4 (« Multiple »), l’unité correspond à des demi-lignes. Défaut : 0 |

 **Retour :**
void


---


### setRowGapRule {#setRowGapRule}

| Nom | Description |
| --- | --- |
| setRowGapRule (int) | Type d’espacement vertical entre les lignes d’une matrice ; les unités peuvent être des lignes ou des points (stockés en twips). Défaut : SingleSpacingGap (0) |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathLimit](../mathlimit)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathMatrix](../mathmatrix)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathBlock](../mathblock)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathRadical](../mathradical)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathArray](../matharray)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathPhantom](../mathphantom)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathDelimiter](../mathdelimiter)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathNaryOperator](../mathnaryoperator)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathAccent](../mathaccent)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathBorderBox](../mathborderbox)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathGroupingCharacter](../mathgroupingcharacter)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathBar](../mathbar)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
| column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathSuperscriptElement](../mathsuperscriptelement)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathFunction](../mathfunction)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathSubscriptElement](../mathsubscriptelement)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathFraction](../mathfraction)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathematicalText](../mathematicaltext)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [BaseScript](../basescript)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathBox](../mathbox)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathElementBase](../mathelementbase)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, int, [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Élément de la matrice |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| row | int | L’index basé sur zéro de la ligne dont on veut l’élément |
 | column | int | L’index basé sur zéro de la colonne dont on veut l’élément |

 **Retour :**
void

---