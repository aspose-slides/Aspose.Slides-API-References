---
title: ChartDataPoint
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le point de données de la série.
type: docs
url: /fr/com.aspose.slides/chartdatapoint/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Représente le point de données de la série.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Renvoie la valeur de taille du point de données du graphique. |
| [getColorValue()](#getColorValue--) | Renvoie la valeur de couleur du point de données du graphique. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Représente les valeurs des barres d’erreur de la série dans le cas d’un type de valeur Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Indique que les bulles ont un effet 3-D appliqué. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Indique que les bulles ont un effet 3-D appliqué. |
| [getExplosion()](#getExplosion--) | Indique la quantité que le point de données doit être déplacé du centre du secteur. |
| [setExplosion(int value)](#setExplosion-int-) | Indique la quantité que le point de données doit être déplacé du centre du secteur. |
| [getFormat()](#getFormat--) | Représente les propriétés de formatage. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente les propriétés de formatage. |
| [getMarker()](#getMarker--) | Indique un marqueur de données. |
| [getSetAsTotal()](#getSetAsTotal--) | Définit le point de données comme total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Définit le point de données comme total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Supprime le DataPoint de la série du graphique. |
| [getDataPointLevels()](#getDataPointLevels--) | Renvoie le conteneur des niveaux de points de données. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Renvoie une couleur automatique du point de données basée sur l’index de la série, l’index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Indique que le point de données doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Indique que le point de données doit inverser ses couleurs si la valeur est négative. |
| [getActualX()](#getActualX--) | Indique la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualY()](#getActualY--) | Indique le haut réel de l’élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualWidth()](#getActualWidth--) | Indique la largeur réelle de l’élément du graphique. |
| [getActualHeight()](#getActualHeight--) | Indique la hauteur réelle de l’élément du graphique. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Lecture seule [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Valeur de retour :**  
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Valeur de retour :**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Valeur de retour :**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Valeur de retour :**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Renvoie la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Valeur de retour :**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Renvoie la valeur de couleur du point de données du graphique. Utilisé avec les graphiques Map. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Valeur de retour :**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Représente les valeurs des barres d’erreur de la série dans le cas d’un type de valeur Custom. Lecture seule [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Valeur de retour :**  
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Lecture seule [IDataLabel](../../com.aspose.slides/idatalabel).

**Valeur de retour :**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Indique que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean.

**Valeur de retour :**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Indique que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Indique la quantité que le point de données doit être déplacé du centre du secteur. Lecture/écriture int.

**Valeur de retour :**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Indique la quantité que le point de données doit être déplacé du centre du secteur. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Représente les propriétés de formatage. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Valeur de retour :**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Représente les propriétés de formatage. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Indique un marqueur de données. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Valeur de retour :**  
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall.

**Valeur de retour :**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Valeur de retour :**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Supprime le DataPoint de la série du graphique.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Renvoie le conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst. L’indexation des niveaux de points de données commence à zéro.

**Valeur de retour :**  
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Valeur de retour :**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Valeur de retour :**  
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Renvoie une couleur automatique du point de données basée sur l’index de la série, l’index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined.

**Valeur de retour :**  
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Indique que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Valeur de retour :**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Indique que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Indique la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture float.

**Valeur de retour :**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Indique le haut réel de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture float.

**Valeur de retour :**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Indique la largeur réelle de l’élément du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture float.

**Valeur de retour :**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Indique la hauteur réelle de l’élément du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture float.

**Valeur de retour :**  
float