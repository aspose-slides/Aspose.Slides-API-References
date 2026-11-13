---
title: ChartDataPoint
second_title: Référence de l'API Aspose.Slides for Java
description: Représente un point de données de série.
type: docs
url: /fr/com.aspose.slides/chartdatapoint/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Représente un point de données de série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Retourne la valeur de taille du point de données du graphique. |
| [getColorValue()](#getColorValue--) | Retourne la valeur de couleur du point de données du graphique. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Représente les valeurs des barres d'erreur de série dans le cas d'un type de valeur Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Spécifie que les bulles ont un effet 3-D appliqué. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Spécifie que les bulles ont un effet 3-D appliqué. |
| [getExplosion()](#getExplosion--) | Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. |
| [setExplosion(int value)](#setExplosion-int-) | Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. |
| [getFormat()](#getFormat--) | Représente les propriétés de mise en forme. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente les propriétés de mise en forme. |
| [getMarker()](#getMarker--) | Spécifie un marqueur de données. |
| [getSetAsTotal()](#getSetAsTotal--) | Définit le point de données comme total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Définit le point de données comme total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique provenant de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Supprime le DataPoint de la série de graphique. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourne le conteneur des niveaux du point de données. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourne une couleur automatique du point de données basée sur l'indice de série, l'indice du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. |
| [getCachedValue()](#getCachedValue--) | Obtient la valeur mise en cache d'un point de données du graphique. |
| [getCachedXValue()](#getCachedXValue--) | Obtient la valeur X mise en cache d'un point de données du graphique. |
| [getCachedYValue()](#getCachedYValue--) | Obtient la valeur Y mise en cache d'un point de données du graphique. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Obtient la taille de bulle mise en cache d'un point de données du graphique. |
| [getActualX()](#getActualX--) | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualY()](#getActualY--) | Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualWidth()](#getActualWidth--) | Spécifie la largeur réelle de l'élément du graphique. |
| [getActualHeight()](#getActualHeight--) | Spécifie la hauteur réelle de l'élément du graphique. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Lecture seule [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retour :**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Retourne la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Retourne la valeur de couleur du point de données du graphique. Utilisé avec les graphiques Cartes. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Représente les valeurs des barres d'erreur de série dans le cas d'un type de valeur Custom. Lecture seule [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retour :**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Lecture seule [IDataLabel](../../com.aspose.slides/idatalabel).

**Retour :**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture booléen.

**Retour :**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. Lecture/écriture int.

**Retour :**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Spécifie la distance à laquelle le point de données doit être déplacé depuis le centre du secteur. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Représente les propriétés de mise en forme. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Retour :**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Représente les propriétés de mise en forme. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Spécifie un marqueur de données. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Retour :**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall.

**Retour :**
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

Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique provenant de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

Supprime le DataPoint de la série de graphique.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Retourne le conteneur des niveaux du point de données. Appliqué pour les séries Treeamp et Sunburst. L'indexation des niveaux du point de données commence à zéro.

**Retour :**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**Retour :**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourne l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retour :**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Retourne une couleur automatique du point de données basée sur l'indice de série, l'indice du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined.

**Retour :**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture booléen.

**Retour :**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Obtient la valeur mise en cache d'un point de données du graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs mises en cache de la série du graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Obtient la valeur X mise en cache d'un point de données du graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs X mises en cache de la série du graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Obtient la valeur Y mise en cache d'un point de données du graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs Y mises en cache de la série du graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Obtient la taille de bulle mise en cache d'un point de données du graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs de taille de bulle mises en cache de la série du graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Retour :**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Retour :**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Retour :**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Retour :**
float