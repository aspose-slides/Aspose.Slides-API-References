---
title: IChartDataPoint
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le point de données de la série.
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
| [getXValue()](#getXValue--) | Obtient la valeur x d'un point de données de graphique. |
| [getYValue()](#getYValue--) | Obtient la valeur y d'un point de données de graphique. |
| [getBubbleSize()](#getBubbleSize--) | Obtient la taille de la bulle d'un point de données de graphique. |
| [getValue()](#getValue--) | Obtient la valeur d'un point de données de graphique. |
| [getCachedXValue()](#getCachedXValue--) | Obtient la valeur X en cache d'un point de données de graphique. |
| [getCachedYValue()](#getCachedYValue--) | Obtient la valeur Y en cache d'un point de données de graphique. |
| [getCachedValue()](#getCachedValue--) | Obtient la valeur en cache d'un point de données de graphique. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Obtient la taille de la bulle en cache d'un point de données de graphique. |
| [getSizeValue()](#getSizeValue--) | Obtient la valeur de taille d'un point de données de graphique. |
| [getColorValue()](#getColorValue--) | Obtient la valeur de couleur d'un point de données de graphique. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Représente les valeurs des barres d'erreur de la série dans le cas d'un type de valeur Personnalisé. |
| [getLabel()](#getLabel--) | Représente l'étiquette du point de données du graphique. |
| [isBubble3D()](#isBubble3D--) | Indique que les bulles ont un effet 3D appliqué. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Indique que les bulles ont un effet 3D appliqué. |
| [getExplosion()](#getExplosion--) | Indique la distance à laquelle le point de données doit être déplacé du centre du secteur. |
| [setExplosion(int value)](#setExplosion-int-) | Indique la distance à laquelle le point de données doit être déplacé du centre du secteur. |
| [getFormat()](#getFormat--) | Représente les propriétés de mise en forme. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente les propriétés de mise en forme. |
| [getMarker()](#getMarker--) | Indique un marqueur de données. |
| [remove()](#remove--) | Supprime le DataPoint de la série de graphique. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Renvoie une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Définit le point de données comme total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Définit le point de données comme total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Indique que le point de données doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Indique que le point de données doit inverser ses couleurs si la valeur est négative. |
| [getDataPointLevels()](#getDataPointLevels--) | Renvoie le conteneur des niveaux du point de données. |
| [getIndex()](#getIndex--) | Détermine à quelle collection d'enfants du parent ce point de données s'applique. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Obtient la valeur x d'un point de données de graphique. Lecture seule [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Renvoie :**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Obtient la valeur y d'un point de données de graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Obtient la taille de la bulle d'un point de données de graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Obtient la valeur d'un point de données de graphique. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Obtient la valeur X en cache d'un point de données de graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs X en cache de la série de graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Renvoie :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

Obtient la valeur Y en cache d'un point de données de graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs Y en cache de la série de graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Obtient la valeur en cache d'un point de données de graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs en cache de la série de graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Obtient la taille de la bulle en cache d'un point de données de graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Affiche toutes les valeurs de taille de bulle en cache de la série de graphique.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Obtient la valeur de taille d'un point de données de graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Obtient la valeur de couleur d'un point de données de graphique. Utilisé avec les graphiques Map. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie :**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Représente les valeurs des barres d'erreur de la série dans le cas d'un type de valeur Personnalisé. Lecture seule [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Renvoie :**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Représente l'étiquette du point de données du graphique. Lecture seule [IDataLabel](../../com.aspose.slides/idatalabel).

**Renvoie :**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Indique que les bulles ont un effet 3D appliqué. Lecture/écriture boolean.

**Renvoie :**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Indique que les bulles ont un effet 3D appliqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Indique la distance à laquelle le point de données doit être déplacé du centre du secteur. Lecture/écriture int.

**Renvoie :**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Indique la distance à laquelle le point de données doit être déplacé du centre du secteur. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Représente les propriétés de mise en forme. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Représente les propriétés de mise en forme. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Indique un marqueur de données. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Renvoie :**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Supprime le DataPoint de la série de graphique.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Renvoie une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined.

**Renvoie :**
java.awt.Color - Couleur automatique du point de données java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Renvoie :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Définit le point de données comme total. Appliqué uniquement aux séries de type Waterfall.

**Renvoie :**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Définit le point de données comme total. Appliqué uniquement aux séries de type Waterfall.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Indique que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Renvoie :**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Indique que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Renvoie le conteneur des niveaux du point de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux du point de données commence à zéro.

**Renvoie :**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Détermine à quelle collection d'enfants du parent ce point de données s'applique. Lecture long.

**Renvoie :**
long