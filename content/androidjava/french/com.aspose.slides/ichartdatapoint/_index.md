---
title: IChartDataPoint
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le point de données d’une série.
type: docs
url: /fr/com.aspose.slides/ichartdatapoint/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Représente le point de données de la série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXValue()](#getXValue--) | Renvoie la valeur x du point de données du graphique. |
| [getYValue()](#getYValue--) | Renvoie la valeur y du point de données du graphique. |
| [getBubbleSize()](#getBubbleSize--) | Renvoie la taille de la bulle du point de données du graphique. |
| [getValue()](#getValue--) | Renvoie la valeur du point de données du graphique. |
| [getSizeValue()](#getSizeValue--) | Renvoie la valeur de taille du point de données du graphique. |
| [getColorValue()](#getColorValue--) | Renvoie la valeur de couleur du point de données du graphique. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Représente les valeurs des barres d’erreur de la série dans le cas du type de valeur Custom. |
| [getLabel()](#getLabel--) | Représente le libellé du point de données du graphique. |
| [isBubble3D()](#isBubble3D--) | Spécifie que les bulles ont un effet 3-D appliqué. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Spécifie que les bulles ont un effet 3-D appliqué. |
| [getExplosion()](#getExplosion--) | Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. |
| [setExplosion(int value)](#setExplosion-int-) | Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. |
| [getFormat()](#getFormat--) | Représente les propriétés de formatage. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente les propriétés de formatage. |
| [getMarker()](#getMarker--) | Spécifie un marqueur de données. |
| [remove()](#remove--) | Supprime le DataPoint de la série du graphique. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Renvoie une couleur automatique du point de données en fonction de l’index de la série, de l’index du point de données, de la propriété ParentSeriesGroup.IsColorVaried et du style du graphique. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Définit le point de données comme total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Définit le point de données comme total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. |
| [getDataPointLevels()](#getDataPointLevels--) | Renvoie le conteneur des niveaux de points de données. |
| [getIndex()](#getIndex--) | Détermine à laquelle des collections d’enfants du parent ce point de données s’applique. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Renvoie la valeur x du point de données du graphique. Lecture seule [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Renvoie :**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Renvoie la valeur y du point de données du graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Renvoie la taille de la bulle du point de données du graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Renvoie la valeur du point de données du graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Renvoie la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Renvoie la valeur de couleur du point de données du graphique. Utilisé avec les graphiques Cartes. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Représente les valeurs des barres d’erreur de la série dans le cas du type de valeur Custom. Lecture seule [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Renvoie :**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Représente le libellé du point de données du graphique. Lecture seule [IDataLabel](../../com.aspose.slides/idatalabel).

**Renvoie :**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. Lecture/écriture int.

**Renvoie :**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Représente les propriétés de formatage. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Représente les propriétés de formatage. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Spécifie un marqueur de données. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Renvoie :**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Supprime le DataPoint de la série du graphique.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Renvoie une couleur automatique du point de données en fonction de l’index de la série, de l’index du point de données, de la propriété ParentSeriesGroup.IsColorVaried et du style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined.

**Renvoie :**
java.lang.Integer - Couleur automatique du point de données java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Renvoie :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall.

**Renvoie :**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Renvoie :**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Renvoie le conteneur des niveaux de points de données. Appliqué pour les séries TreeMap et Sunburst. L’indexation des niveaux de points de données commence à zéro.

**Renvoie :**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Détermine à laquelle des collections d’enfants du parent ce point de données s’applique. Lecture long.

**Renvoie :**
long