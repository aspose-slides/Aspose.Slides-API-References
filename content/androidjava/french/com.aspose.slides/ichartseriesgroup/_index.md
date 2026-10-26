---
title: IChartSeriesGroup
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un groupe de séries.
type: docs
url: /fr/com.aspose.slides/ichartseriesgroup/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Représente un groupe de séries.

--------------------

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup.  
2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« series group properties »). « Series group properties » dans la classe ChartSeriesGroup est en lecture/écriture. Chaque « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie un type de ce groupe de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. |
| [getSeries()](#getSeries--) | Renvoie une collection en lecture seule de séries de graphique. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUpDownBars()](#getUpDownBars--) | Fournit l'accès aux barres haut/bas du graphique en ligne ou en actions. |
| [getGapWidth()](#getGapWidth--) | Spécifie l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [setGapWidth(int value)](#setGapWidth-int-) | Spécifie l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtient ou définit l'angle de la première tranche de graphique circulaire ou anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtient ou définit l'angle de la première tranche de graphique circulaire ou anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque marqueur de données de la série a une couleur différente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Spécifie que chaque marqueur de données de la série a une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Vrai si le graphique possède des lignes de séries. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vrai si le graphique possède des lignes de séries. |
| [getOverlap()](#getOverlap--) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Spécifie la taille du deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Spécifie une valeur utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur. |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisée pour un graphique multi-secteur ou barre-de-secteur avec une division personnalisée. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou d'un graphique en anneau (peut être entre 10 et 90 % de la taille de la zone de tracé). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Spécifie la taille du trou d'un graphique en anneau (peut être entre 10 et 90 % de la taille de la zone de tracé). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Spécifie le format HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille de bulles sont représentées sur le graphique à bulles. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Spécifie comment les valeurs de taille de bulles sont représentées sur le graphique à bulles. |

### getType() {#getType--}
```
public abstract int getType()
```

Renvoie un type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Renvoie :**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indique si les séries de ce groupe sont tracées sur l'axe secondaire. Lecture seule boolean.

**Renvoie :**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Renvoie une collection en lecture seule de séries de graphique. Lecture seule [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Renvoie :**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Fournit l'accès aux barres haut/bas du graphique en ligne ou en actions. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Renvoie :**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Spécifie l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Renvoie :**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Spécifie l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Renvoie :**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Obtient ou définit l'angle de la première tranche de graphique circulaire ou anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Renvoie :**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Obtient ou définit l'angle de la première tranche de graphique circulaire ou anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écriture boolean.

**Renvoie :**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et aux graphiques OfPie. Lecture/écriture boolean.

**Renvoie :**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et aux graphiques OfPie. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). - -100 % : Espacement maximal (les barres sont complètement séparées). - 0 % : Les barres sont placées côte à côte sans chevauchement ni espacement. - 100 % : Chevauchement maximal (les barres se chevauchent entièrement). Cette propriété est en lecture/écriture byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définit le chevauchement à 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This property is read/write byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définit le chevauchement à 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Returns:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Returns:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Returns:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique multi-secteur ou barre-de-secteur. Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). Read/write byte.

**Returns:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Returns:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Spécifie le facteur d'échelle pour le graphique à bulles (peut être compris entre 0 et 300 % de la taille par défaut). Lecture/écriture int.

**Returns:**
int
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returns:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)

Spécifie comment les valeurs de taille de bulles sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |