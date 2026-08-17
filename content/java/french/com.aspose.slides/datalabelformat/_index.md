---
title: DataLabelFormat
second_title: Référence API Aspose.Slides for Java
description: Représente les options de formatage pour DataLabel.
type: docs
url: /fr/com.aspose.slides/datalabelformat/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Représente les options de formatage pour DataLabel.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lecture/écriture booléen. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lecture/écriture booléen. |
| [getNumberFormat()](#getNumberFormat--) | Représente la chaîne de format pour l'objet DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Représente la chaîne de format pour l'objet DataLabels. |
| [getFormat()](#getFormat--) | Représente le format de l'étiquette de données. |
| [getPosition()](#getPosition--) | Représente le format de l'étiquette de données. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'étiquette de données. |
| [getShowLegendKey()](#getShowLegendKey--) | Représente la position de l'étiquette de données. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un graphique spécifié. |
| [getShowValue()](#getShowValue--) | Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un graphique spécifié. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. |
| [getShowCategoryName()](#getShowCategoryName--) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. |
| [getShowSeriesName()](#getShowSeriesName--) | Renvoie ou définit un booléen pour indiquer le comportement d'affichage du nom de série pour les étiquettes de données d'un graphique. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Renvoie ou définit un booléen pour indiquer le comportement d'affichage du nom de série pour les étiquettes de données d'un graphique. |
| [getShowPercentage()](#getShowPercentage--) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un graphique spécifié. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un graphique spécifié. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Représente le comportement d'affichage des lignes directrices d'étiquette de données d'un graphique spécifié. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Représente le comportement d'affichage des lignes directrices d'étiquette de données d'un graphique spécifié. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un graphique spécifié. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un graphique spécifié. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme appel de données ou comme étiquette de données. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme appel de données ou comme étiquette de données. |
| [getSeparator()](#getSeparator--) | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. |
| [getTextFormat()](#getTextFormat--) | Renvoie le format de texte du graphique. |
| [getChart()](#getChart--) | Renvoie le graphique. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie:**  
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" entraîne que tous les DataLabels.get_Item(i).isNumberFormatLinkedToSource() sont égaux à val).

**Renvoie:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" entraîne que tous les DataLabels.get_Item(i).isNumberFormatLinkedToSource() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également définie pour la propriété NumberFormat de toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" entraîne que tous les DataLabels.get_Item(i).getNumberFormat() sont égaux à val).

**Renvoie:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également définie pour la propriété NumberFormat de toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" entraîne que tous les DataLabels.get_Item(i).getNumberFormat() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Représente le format de l'étiquette de données. Lecture seule [IFormat](../../com.aspose.slides/iformat).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété représente le format par défaut pour les nouvelles étiquettes de données dans la collection DataLabelCollection.

**Renvoie:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Représente la position de l'étiquette de données. Lecture/écriture [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position pour les objets DataLabel. Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setPosition(val);" entraîne que tous les DataLabels.get_Item(i).getPosition() sont égaux à val).

**Renvoie:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Représente la position de l'étiquette de données. Lecture/écriture [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position pour les objets DataLabel. Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setPosition(val);" entraîne que tous les DataLabels.get_Item(i).getPosition() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" entraîne que tous les DataLabels.get_Item(i).getShowLegendKey() sont égaux à val).

**Renvoie:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" entraîne que tous les DataLabels.get_Item(i).getShowLegendKey() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" entraîne que tous les DataLabels.get_Item(i).getShowValue() sont égaux à val).

**Renvoie:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" entraîne que tous les DataLabels.get_Item(i).getShowValue() sont égaux à val).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données d'un graphique. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" entraîne que tous les DataLabels.get_Item(i).getShowCategoryName() sont égaux à val).

**Renvoie:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données d'un graphique. False pour masquer. Lecture/écriture booléen.
Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause que toutes les DataLabels.get_Item(i).getShowCategoryName() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Renvoie ou définit un Boolean pour indiquer le comportement d’affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause que toutes les DataLabels.get_Item(i).getShowSeriesName() soient égales à val).

**Renvoie :**  
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Renvoie ou définit un Boolean pour indiquer le comportement d’affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause que toutes les DataLabels.get_Item(i).getShowSeriesName() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Représente le comportement d’affichage de la valeur de pourcentage des étiquettes de données d’un graphique spécifié. True affiche la valeur du pourcentage. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause que toutes les DataLabels.get_Item(i).getShowPercentage() soient égales à val).

**Renvoie :**  
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Représente le comportement d’affichage de la valeur de pourcentage des étiquettes de données d’un graphique spécifié. True affiche la valeur du pourcentage. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause que toutes les DataLabels.get_Item(i).getShowPercentage() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Représente le comportement d’affichage de la valeur de taille de bulle des étiquettes de données d’un graphique spécifié. True affiche la valeur de taille de bulle. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause que toutes les DataLabels.get_Item(i).getShowBubbleSize() soient égales à val).

**Renvoie :**  
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Représente le comportement d’affichage de la valeur de taille de bulle des étiquettes de données d’un graphique spécifié. True affiche la valeur de taille de bulle. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause que toutes les DataLabels.get_Item(i).getShowBubbleSize() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Représente le comportement d’affichage des lignes de leader des étiquettes de données d’un graphique spécifié. True affiche les lignes de leader. False les masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause que toutes les DataLabels.get_Item(i).getShowLeaderLines() soient égales à val).

**Renvoie :**  
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Représente le comportement d’affichage des lignes de leader des étiquettes de données d’un graphique spécifié. True affiche les lignes de leader. False les masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause que toutes les DataLabels.get_Item(i).getShowLeaderLines() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Représente le comportement d’affichage de la valeur de cellule des étiquettes de données d’un graphique spécifié. True affiche la valeur de la cellule. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dit

 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause que toutes les DataLabels.get_Item(i).getShowLabelValueFromCell() soient égales à val).

**Renvoie :**  
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Représente le comportement d’affichage de la valeur de cellule des étiquettes de données d’un graphique spécifié. True affiche la valeur de la cellule. False la masque. Lecture/écriture boolean.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause que toutes les DataLabels.get_Item(i).getShowLabelValueFromCell() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Détermine si l’étiquette de données d’un graphique spécifié sera affichée comme infobulle de données ou comme étiquette de données.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause que toutes les DataLabels.get_Item(i).getShowLabelAsDataCallout() soient égales à val).

**Renvoie :**  
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Détermine si l’étiquette de données d’un graphique spécifié sera affichée comme infobulle de données ou comme étiquette de données.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dit

 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause que toutes les DataLabels.get_Item(i).getShowLabelAsDataCallout() soient égales à val).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause que toutes les DataLabels.get_Item(i).getSeparator() soient égales à val).

**Renvoie :**  
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données dans la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause que toutes les DataLabels.get_Item(i).getSeparator() soient égales à val).
**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Renvoie le format du texte du graphique. Lecture seule [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Renvoie:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Renvoie le graphique. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie:**
[IChart](../../com.aspose.slides/ichart)