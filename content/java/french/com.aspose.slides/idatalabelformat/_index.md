---
title: IDataLabelFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les options de formatage pour DataLabel.
type: docs
url: /fr/com.aspose.slides/idatalabelformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Représente les options de formatage pour DataLabel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lecture/écriture boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lecture/écriture boolean. |
| [getNumberFormat()](#getNumberFormat--) | Représente la chaîne de format pour l'objet DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Représente la chaîne de format pour l'objet DataLabels. |
| [getFormat()](#getFormat--) | Représente le format de l'étiquette de données. |
| [getPosition()](#getPosition--) | Représente la position de l'étiquette de données. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'étiquette de données. |
| [getShowLegendKey()](#getShowLegendKey--) | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. |
| [getShowValue()](#getShowValue--) | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. |
| [getShowCategoryName()](#getShowCategoryName--) | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. |
| [getShowSeriesName()](#getShowSeriesName--) | Renvoie ou définit un boolean indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un graphique. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Renvoie ou définit un boolean indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un graphique. |
| [getShowPercentage()](#getShowPercentage--) | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Représente le comportement d'affichage de la taille de bulle de l'étiquette de données d'un graphique spécifié. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Représente le comportement d'affichage de la taille de bulle de l'étiquette de données d'un graphique spécifié. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Représente le comportement d'affichage des lignes directrices de l'étiquette de données d'un graphique spécifié. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Représente le comportement d'affichage des lignes directrices de l'étiquette de données d'un graphique spécifié. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme une annotation de données ou comme une étiquette de données. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme une annotation de données ou comme une étiquette de données. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. |
| [getSeparator()](#getSeparator--) | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété IsNumberFormatLinkedToSource de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" entraîne que tous les DataLabels.get\_Item(i).isNumberFormatLinkedToSource() sont égaux à val).

**Retour:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété IsNumberFormatLinkedToSource de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" entraîne que tous les DataLabels.get\_Item(i).isNumberFormatLinkedToSource() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" entraîne que tous les DataLabels.get\_Item(i).getNumberFormat() sont égaux à val).

**Retour:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" entraîne que tous les DataLabels.get\_Item(i).getNumberFormat() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Représente le format de l'étiquette de données. Lecture seule [IFormat](../../com.aspose.slides/iformat).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété représente le format par défaut des nouvelles étiquettes de données dans la collection DataLabelCollection.

**Retour:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Représente la position de l'étiquette de données. Lecture/écriture [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position des objets DataLabel. Définir cette propriété avec une valeur définit également cette valeur pour la propriété Position de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" entraîne que tous les DataLabels.get\_Item(i).getPosition() sont égaux à val).

**Retour:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Représente la position de l'étiquette de données. Lecture/écriture [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position des objets DataLabel. Définir cette propriété avec une valeur définit également cette valeur pour la propriété Position de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" entraîne que tous les DataLabels.get\_Item(i).getPosition() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLegendKey de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" entraîne que tous les DataLabels.get\_Item(i).getShowLegendKey() sont égaux à val).

**Retour:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLegendKey de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" entraîne que tous les DataLabels.get\_Item(i).getShowLegendKey() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowValue de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" entraîne que tous les DataLabels.get\_Item(i).getShowValue() sont égaux à val).

**Retour:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowValue de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" entraîne que tous les DataLabels.get\_Item(i).getShowValue() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie des étiquettes de données sur un graphique. False pour masquer. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowCategoryName de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" entraîne que tous les DataLabels.get\_Item(i).getShowCategoryName() sont égaux à val).

**Retour:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie des étiquettes de données sur un graphique. False pour masquer. Lecture/écriture boolean.

--------------------
Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowCategoryName() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Renvoie ou définit un booléen indiquant le comportement d’affichage du nom de série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowSeriesName() sont égaux à val).

**Retour :**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Renvoie ou définit un booléen indiquant le comportement d’affichage du nom de série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowSeriesName() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Représente le comportement d’affichage de la valeur de pourcentage des étiquettes de données d’un graphique spécifié. True affiche la valeur de pourcentage. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowPercentage() sont égaux à val).

**Retour :**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Représente le comportement d’affichage de la valeur de pourcentage des étiquettes de données d’un graphique spécifié. True affiche la valeur de pourcentage. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowPercentage() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Représente le comportement d’affichage de la taille de la bulle des étiquettes de données d’un graphique spécifié. True affiche la taille de la bulle. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowBubbleSize() sont égaux à val).

**Retour :**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Représente le comportement d’affichage de la taille de la bulle des étiquettes de données d’un graphique spécifié. True affiche la taille de la bulle. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowBubbleSize() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. True affiche les lignes de repère. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLeaderLines() sont égaux à val).

**Retour :**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. True affiche les lignes de repère. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLeaderLines() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCalloff()
```

Détermine si l’étiquette de données d’un graphique spécifié sera affichée comme appel de données ou comme étiquette de données.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLabelAsDataCallout() sont égaux à val).

**Retour :**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Détermine si l’étiquette de données d’un graphique spécifié sera affichée comme appel de données ou comme étiquette de données.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLabelAsDataCallout() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Représente le comportement d’affichage de la valeur de cellule des étiquettes de données d’un graphique spécifié. True affiche la valeur de cellule. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLabelValueFromCell() sont égaux à val).

**Retour :**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Représente le comportement d’affichage de la valeur de cellule des étiquettes de données d’un graphique spécifié. True affiche la valeur de cellule. False masque. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getShowLabelValueFromCell() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Définit ou renvoie une variante représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getSeparator() sont égaux à val).

**Retour :**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Définit ou renvoie une variante représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ce qui entraîne que tous les DataLabels.get_Item(i).getSeparator() sont égaux à val).
**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |