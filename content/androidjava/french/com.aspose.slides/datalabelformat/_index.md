---
title: DataLabelFormat
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente les options de formatage pour DataLabel.
type: docs
url: /fr/com.aspose.slides/datalabelformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
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
| [getPosition()](#getPosition--) | Représente la position de l'étiquette de données. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'étiquette de données. |
| [getShowLegendKey()](#getShowLegendKey--) | Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un diagramme spécifié. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un diagramme spécifié. |
| [getShowValue()](#getShowValue--) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un diagramme spécifié. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un diagramme spécifié. |
| [getShowCategoryName()](#getShowCategoryName--) | Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un diagramme spécifié. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un diagramme spécifié. |
| [getShowSeriesName()](#getShowSeriesName--) | Retourne ou définit un booléen indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un diagramme. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Retourne ou définit un booléen indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un diagramme. |
| [getShowPercentage()](#getShowPercentage--) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un diagramme spécifié. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un diagramme spécifié. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un diagramme spécifié. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un diagramme spécifié. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Représente le comportement d'affichage des lignes de repère d'étiquette de données d'un diagramme spécifié. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Représente le comportement d'affichage des lignes de repère d'étiquette de données d'un diagramme spécifié. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un diagramme spécifié. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un diagramme spécifié. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Détermine si l'étiquette de données d'un diagramme spécifié sera affichée comme appel de données ou comme étiquette de données. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Détermine si l'étiquette de données d'un diagramme spécifié sera affichée comme appel de données ou comme étiquette de données. |
| [getSeparator()](#getSeparator--) | Définit ou retourne un Variant représentant le séparateur utilisé pour les étiquettes de données d'un diagramme. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Définit ou retourne un Variant représentant le séparateur utilisé pour les étiquettes de données d'un diagramme. |
| [getTextFormat()](#getTextFormat--) | Retourne le format de texte du diagramme. |
| [getChart()](#getChart--) | Retourne le diagramme. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Retourne :**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" provoque que tous les DataLabels.get_Item(i).isNumberFormatLinkedToSource() soient égaux à val).

**Retourne :**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" provoque que tous les DataLabels.get_Item(i).isNumberFormatLinkedToSource() soient égaux à val).

**Paramètres :**
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

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get\_Item(i).getNumberFormat() to equal to val).

**Returns:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Represents the format string for the DataLabels object. Read/write String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Represents the format of the data label. Read-only [IFormat](../../com.aspose.slides/iformat).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection.

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```
Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Returns:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Représente le comportement d'affichage de la clé de légende d'étiquette de données d'un diagramme spécifié. Vrai si la clé de légende d'étiquette de données est visible. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" entraîne que tous les DataLabels.get_Item(i).getShowLegendKey() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Returns:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un diagramme spécifié. True pour afficher le nom de catégorie des étiquettes de données sur un diagramme. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" entraîne que tous les DataLabels.get_Item(i).getShowCategoryName() sont égaux à val).

**Retourne :**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un diagramme spécifié. True pour afficher le nom de catégorie des étiquettes de données sur un diagramme. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" entraîne que tous les DataLabels.get_Item(i).getShowCategoryName() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Retourne ou définit un booléen indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un diagramme. True pour afficher le nom de série. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" entraîne que tous les DataLabels.get_Item(i).getShowSeriesName() sont égaux à val).

**Retourne :**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```


Retourne ou définit un booléen indiquant le comportement d'affichage du nom de série pour les étiquettes de données d'un diagramme. True pour afficher le nom de série. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" entraîne que tous les DataLabels.get_Item(i).getShowSeriesName() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Returns:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un diagramme spécifié. True affiche la valeur de taille de bulle. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" entraîne que tous les DataLabels.get_Item(i).getShowBubbleSize() sont égaux à val).

**Retourne :**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un diagramme spécifié. True affiche la valeur de taille de bulle. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" entraîne que tous les DataLabels.get_Item(i).getShowBubbleSize() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```
Représente le comportement d'affichage des lignes de repère d'étiquette de données d'un diagramme spécifié. True affiche les lignes de repère. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" entraîne que tous les DataLabels.get_Item(i).getShowLeaderLines() sont égaux à val).

**Returns:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Représente le comportement d'affichage des lignes de repère d'étiquette de données d'un diagramme spécifié. True affiche les lignes de repère. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" entraîne que tous les DataLabels.get_Item(i).getShowLeaderLines() sont égaux à val).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un diagramme spécifié. True affiche la valeur de la cellule. False pour masquer. Lecture/écriture booléen.

--------------------

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Returns:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Returns:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Returns chart text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()


Retourne le diagramme. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Retourne :**
[IChart](../../com.aspose.slides/ichart)