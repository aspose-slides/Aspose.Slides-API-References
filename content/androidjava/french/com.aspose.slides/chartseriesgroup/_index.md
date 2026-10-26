---
title: ChartSeriesGroup
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un groupe de séries.
type: docs
url: /fr/com.aspose.slides/chartseriesgroup/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Représente un groupe de séries.

--------------------

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« series group properties »). Les « series group properties » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie un type de ce groupe de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. |
| [getSeries()](#getSeries--) | Renvoie une collection de séries. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUpDownBars()](#getUpDownBars--) | Fournit l'accès aux barres haut/bas d'un graphique en ligne ou boursier. |
| [getGapWidth()](#getGapWidth--) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [setGapWidth(int value)](#setGapWidth-int-) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou de donut, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou de donut, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [getOverlap()](#getOverlap--) | Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d'un diagramme à deux niveaux, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Spécifie la taille du deuxième secteur ou barre d'un diagramme à deux niveaux, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille des bulles sont représentées sur le diagramme à bulles. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Spécifie comment les valeurs de taille des bulles sont représentées sur le diagramme à bulles. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme à deux niveaux. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme à deux niveaux. |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme à deux niveaux. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme à deux niveaux. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque repère de données dans la série possède une couleur différente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Spécifie que chaque repère de données dans la série possède une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Vrai si le diagramme possède des lignes de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vrai si le diagramme possède des lignes de série. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Spécifie le format des lignes haut/bas. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisée pour un diagramme à deux niveaux avec une division personnalisée. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d'un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Renvoie un type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Renvoie :**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indique si les séries de ce groupe sont tracées sur l'axe secondaire. Lecture seule booléen.

**Renvoie :**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Renvoie une collection de séries. Lecture seule [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Renvoie :**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
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
public final IUpDownBarsManager getUpDownBars()
```

Fournit l'accès aux barres haut/bas d'un graphique en ligne ou boursier. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Renvoie :**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Renvoie :**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Renvoie :**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Obtient ou définit l'angle de la première tranche de diagramme circulaire ou de donut, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Renvoie :**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Obtient ou définit l'angle de la première tranche de diagramme circulaire ou de donut, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Renvoie :**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (barres complètement séparées). -0 % : barres côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (barres se superposent entièrement). Cette propriété est lecture/écriture byte.

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

**Returns:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
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
public final int getSecondPieSize()
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Returns:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returns:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Returns:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Returns:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specifies that each data marker in the series has a different color. Read/write boolean.

**Returns:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Specifies that each data marker in the series has a different color. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```
 
True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean.

**Returns:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```
 
True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean.

**Returns:**
boolean
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Returns:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Returns the parent chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


Renvoie la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)