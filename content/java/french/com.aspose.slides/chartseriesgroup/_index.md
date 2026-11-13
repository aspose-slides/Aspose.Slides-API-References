---
title: ChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un groupe de séries.
type: docs
url: /fr/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Représente un groupe de séries.

--------------------

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des « propriétés du groupe de séries » peut avoir une projection lecture seule dans la classe ChartSeries.

## Méthodes

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie un type de ce groupe de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si les séries de ce groupe sont tracées sur l'axe secondaire. |
| [getSeries()](#getSeries--) | Renvoie une collection de séries. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUpDownBars()](#getUpDownBars--) | Fournit l'accès aux barres haut/bas d'un graphique en ligne ou en chandelier. |
| [getGapWidth()](#getGapWidth--) | Obtient ou définit l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [setGapWidth(int value)](#setGapWidth-int-) | Obtient ou définit l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du repère. |
| [setGapDepth(int value)](#setGapDepth-int-) | Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du repère. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtient ou définit l'angle de la première tranche de graphique en secteur ou en beignet, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtient ou définit l'angle de la première tranche de graphique en secteur ou en beignet, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un graphique en beignet (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Spécifie la taille du trou dans un graphique en beignet (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [getOverlap()](#getOverlap--) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Spécifie la taille du deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur à utiliser pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Spécifie une valeur à utiliser pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque repère de données dans la série a une couleur différente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Spécifie que chaque repère de données dans la série a une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Vrai si le graphique possède des lignes de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vrai si le graphique possède des lignes de série. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Spécifie le format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisées pour un graphique secteur-dans-secteur ou barre-dans-secteur avec une division personnalisée. |
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

Fournit l'accès aux barres haut/bas d'un graphique en ligne ou en chandelier. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Renvoie :**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Obtient ou définit l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Lecture/écriture int.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types Bar (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), sous-types Column (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Renvoie :**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Obtient ou définit l'espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. La valeur doit être comprise entre 0 et 500. Lecture/écriture int.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types Bar (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), sous-types Column (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du repère. La valeur doit être comprise entre 0 et 500. Lecture/écriture int.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types Bar 3D et Column 3D (voir aussi la méthode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Renvoie :**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du repère. La valeur doit être comprise entre 0 et 500. Lecture/écriture int.

--------------------

Cette propriété s'applique aux séries des types suivants : sous-types Bar 3D et Column 3D (voir aussi la méthode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Obtient ou définit l'angle de la première tranche de graphique en secteur ou en beignet, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Renvoie :**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Obtient ou définit l'angle de la première tranche de graphique en secteur ou en beignet, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un graphique en beignet (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Renvoie :**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Spécifie la taille du trou dans un graphique en beignet (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont complètement séparées). -0 % : les barres sont placées côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est lecture/écriture byte.

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


**Renvoie :**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont complètement séparées). -0 % : les barres sont placées côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est lecture/écriture byte.

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
public final int getSecondPieSize()
```

Spécifie la taille du deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). Lecture/écriture int.

**Renvoie :**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Spécifie la taille du deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Renvoie :**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Spécifie une valeur à utiliser pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. Utilisé avec la propriété PieSplitBy. Lecture/écriture double.

**Renvoie :**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Spécifie une valeur à utiliser pour déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. Utilisé avec la propriété PieSplitBy. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Renvoie :**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Spécifie que chaque repère de données dans la série a une couleur différente. Lecture/écriture booléen.

**Renvoie :**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Spécifie que chaque repère de données dans la série a une couleur différente. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture booléen.

**Renvoie :**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Spécifie le format HiLowLines. HiLowLines appliqué aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose.

**Renvoie :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écriture int.

**Renvoie :**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de division personnalisées pour un graphique secteur-dans-secteur ou barre-dans-secteur avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un graphique secteur-dans-secteur ou barre-dans-secteur. Lecture seule [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Renvoie :**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)