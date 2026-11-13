---
title: IChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour Java
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

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« series group properties »). « Series group properties » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune de ces « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Returns a type of this series group. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if series of this group is plotted on secondary axis. |
| [getSeries()](#getSeries--) | Returns a readonly collection of chart series. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUpDownBars()](#getUpDownBars--) | Provede access to up/down bars of Line- or Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Gets or sets the space between bar or column clusters, as a percentage of the bar or column width. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gets or sets the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Gets or sets the distance between data series in a 3D chart, as a percentage of the marker width. |
| [setGapDepth(int value)](#setGapDepth-int-) | Gets or sets the distance between data series in a 3D chart, as a percentage of the marker width. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifies that each data marker in the series has a different color. |
| [hasSeriesLines()](#hasSeriesLines--) | True if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True if chart has series lines. |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifies HiLowLines format. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifies how the bubble size values are represented on the bubble chart. |

### getType() {#getType--}
```
public abstract int getType()
```

Renvoie un type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retour :**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indique si les séries de ce groupe sont tracées sur un axe secondaire. Booléen lecture seule.

**Retour :**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Renvoie une collection en lecture seule de séries de diagramme. Lecture seule [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retour :**
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

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Fournit l'accès aux barres haut/bas du diagramme en ligne ou en cours. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retour :**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Obtient ou définit l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Entier lecture/écriture.

--------------------

Cette propriété s'applique aux séries des types suivants : tous les sous-types de barres et de colonnes, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Retour :**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Obtient ou définit l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Entier lecture/écriture.

--------------------

Cette propriété s'applique aux séries des types suivants : tous les sous-types de barres et de colonnes, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Obtient ou définit la distance entre les séries de données dans un diagramme 3D, en pourcentage de la largeur du marqueur. La valeur doit être comprise entre 0 et 500. Entier lecture/écriture.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types de barres et de colonnes 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Retour :**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Obtient ou définit la distance entre les séries de données dans un diagramme 3D, en pourcentage de la largeur du marqueur. La valeur doit être comprise entre 0 et 500. Entier lecture/écriture.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types de barres et de colonnes 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Obtient ou définit l'angle de la première tranche de diagramme en secteurs ou en beignets, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). Entier lecture/écriture.

**Retour :**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Obtient ou définit l'angle de la première tranche de diagramme en secteurs ou en beignets, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). Entier lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Spécifie que chaque marqueur de données dans la série a une couleur différente. Booléen lecture/écriture.

**Retour :**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Spécifie que chaque marqueur de données dans la série a une couleur différente. Booléen lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Vrai si le diagramme possède des lignes de série. S'applique aux diagrammes à barres empilées et OfPie. Booléen lecture/écriture.

**Retour :**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Vrai si le diagramme possède des lignes de série. S'applique aux diagrammes à barres empilées et OfPie. Booléen lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Spécifie de combien les barres et colonnes doivent se chevaucher sur les diagrammes 2-D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont complètement séparées). -0 % : les barres sont côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est un octet lecture/écriture.

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


**Retour :**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Spécifie de combien les barres et colonnes doivent se chevaucher sur les diagrammes 2-D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont complètement séparées). -0 % : les barres sont côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est un octet lecture/écriture.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Spécifie la taille du deuxième secteur ou de la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). Entier lecture/écriture.

**Retour :**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Spécifie la taille du deuxième secteur ou de la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). Entier lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Double lecture/écriture.

**Retour :**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Double lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Retour :**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de division personnalisée pour un diagramme « pie-of-pie » ou « bar-of-pie » avec division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou la deuxième barre. Lecture seule [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retour :**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un diagramme en beignets (entre 10 % et 90 % de la taille de la zone de traçage). Octet lecture/écriture.

**Retour :**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Spécifie la taille du trou dans un diagramme en beignets (entre 10 % et 90 % de la taille de la zone de traçage). Octet lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Spécifie le facteur d'échelle pour le diagramme à bulles (entre 0 % et 300 % de la taille par défaut). Entier lecture/écriture.

**Retour :**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Spécifie le facteur d'échelle pour le diagramme à bulles (entre 0 % et 300 % de la taille par défaut). Entier lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Spécifie le format HiLowLines. HiLowLines s'applique aux types de diagrammes HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose.

**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retour :**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |