---
title: ChartSeries
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une série de graphique.
type: docs
url: /fr/com.aspose.slides/chartseries/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Représente une série de graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [getExplosion()](#getExplosion--) | La distance d’une part de tarte ouverte du centre du graphique circulaire est exprimée en pourcentage du diamètre de la tarte. |
| [setExplosion(int value)](#setExplosion-int-) | La distance d’une part de tarte ouverte du centre du graphique circulaire est exprimée en pourcentage du diamètre de la tarte. |
| [getSmooth()](#getSmooth--) | Représente le lissage de courbe. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Représente le lissage de courbe. |
| [getName()](#getName--) | Renvoie le nom de la série. |
| [getDataPoints()](#getDataPoints--) | Renvoie la collection de points de données de cette série. |
| [getType()](#getType--) | Renvoie un type de cette série. |
| [setType(int value)](#setType-int-) | Renvoie un type de cette série. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si cette série est tracée sur l’axe secondaire. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indique si cette série est tracée sur l’axe secondaire. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Renvoie le format d’une série. |
| [getOrder()](#getOrder--) | Renvoie l’ordre d’une série. |
| [setOrder(int value)](#setOrder-int-) | Renvoie l’ordre d’une série. |
| [getLabels()](#getLabels--) | Renvoie les Labels d’une série. |
| [getTrendLines()](#getTrendLines--) | Collection de lignes de tendance de séries. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Représente les ErrorBars d’une série avec derection X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Représente les ErrorBars d’une série avec derection Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Représente l’entrée de légende liée à cette série Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Spécifie la forme d’une série d’un graphique à barres 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Spécifie la forme d’une série d’un graphique à barres 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Spécifie la couleur solide inversée pour la série. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Renvoie une couleur automatique de la série basée sur l’indice de la série et le style du graphique. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Représente les points internes. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Représente les points internes. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Représente les points aberrants. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Représente les points aberrants. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Représente les repères de moyenne. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Représente les repères de moyenne. |
| [getShowMeanLine()](#getShowMeanLine--) | Représente la ligne de moyenne. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Représente la ligne de moyenne. |
| [getQuartileMethod()](#getQuartileMethod--) | Représente la méthode du quartile. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Représente la méthode du quartile. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Représente les lignes de connexion. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Représente les lignes de connexion. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Représente la disposition des libellés de catégorie parent. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Représente la disposition des libellés de catégorie parent. |
| [hasUpDownBars()](#hasUpDownBars--) | Détermine si le graphique en ligne ou en cours a des barres haut/bas. |
| [getGapWidth()](#getGapWidth--) | Spécifie l’espacement entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, en pourcentage de la largeur du repère, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Spécifie l’angle de la première part de tarte ou de donut, en degrés (dans le sens des aiguilles d’une montre depuis le haut, de 0 à 360 degrés). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un graphique donut (peut être entre 10 % et 90 % de la taille de la zone de tracé). |
| [getOverlap()](#getOverlap--) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (peut être entre 5 % et 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Détermine s’il existe des lignes de séries pour cette série et les séries apparentées. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille de bulle sont représentées sur le graphique à bulles. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données appartiennent au deuxième secteur ou à la deuxième barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données appartiennent au deuxième secteur ou à la deuxième barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informations de division personnalisée pour un graphique « pie-of-pie » ou « bar-of-pie » avec division personnalisée. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque repère de données dans la série a une couleur différente. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d’échelle pour le graphique à bulles (peut être entre 0 % et 300 % de la taille par défaut). |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d’un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d’un FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**  
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**  
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

La distance d’une part de tarte ouverte du centre du graphique circulaire est exprimée en pourcentage du diamètre de la tarte. Lecture/écriture int.

**Renvoie :**  
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

La distance d’une part de tarte ouverte du centre du graphique circulaire est exprimée en pourcentage du diamètre de la tarte. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Représente le lissage de courbe. True si le lissage de courbe est activé pour le graphique en ligne ou le graphique de dispersion. S’applique uniquement aux graphiques en ligne et aux graphiques de dispersion reliés par des lignes. Lecture/écriture boolean.

**Renvoie :**  
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Représente le lissage de courbe. True si le lissage de courbe est activé pour le graphique en ligne ou le graphique de dispersion. S’applique uniquement aux graphiques en ligne et aux graphiques de dispersion reliés par des lignes. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Renvoie le nom de la série. Lecture seule [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Renvoie :**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Renvoie la collection de points de données de cette série. Lecture seule [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Renvoie :**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Renvoie un type de cette série. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Renvoie :**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Renvoie un type de cette série. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indique si cette série est tracée sur l’axe secondaire. Lecture/écriture boolean.

**Renvoie :**  
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indique si cette série est tracée sur l’axe secondaire. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Lecture seule [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Renvoie :**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Renvoie le format d’une série. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**  
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Renvoie l’ordre d’une série. Lecture/écriture int.

**Renvoie :**  
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Renvoie l’ordre d’une série. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Renvoie les Labels d’une série. Lecture seule [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Renvoie :**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Collection de lignes de tendance de séries. Lecture seule [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Les TrendLines sont disponibles (non null) pour les séries de données dans les graphiques area, bar, column, line, stock, xy (scatter) et bubble 2-D non empilés. Une TrendLine n’est pas disponible pour les séries de données dans tout type de graphique empilé ou 3-D. Les TrendLines ne sont pas non plus disponibles pour les graphiques radar, pie, surface ou donut.

**Renvoie :**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Représente les ErrorBars d’une série avec derection X. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les ErrorBars avec direction X sont disponibles pour les séries de type area, bar, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Renvoie :**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Représente les ErrorBars d’une série avec derection Y. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Renvoie :**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Représente l’entrée de légende liée à cette série Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Renvoie :**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lecture/écriture String.

**Renvoie :**  
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Lecture/écriture String.

**Renvoie :**  
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Lecture/écriture String.

**Renvoie :**  
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Lecture/écriture String.

**Renvoie :**  
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Renvoie :**  
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Spécifie la forme d’une série d’un graphique à barres 3-D. La modification de la valeur de cette propriété peut entraîner la modification automatique du Type de la série. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Renvoie :**  
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Spécifie la forme d’une série d’un graphique à barres 3-D. La modification de la valeur de cette propriété peut entraîner la modification automatique du Type de la série. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Renvoie :**  
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Spécifie la couleur solide inversée pour la série. Pour appliquer le paramètre de couleur, définissez le format de série FillType sur FillType.Solid. Lecture/écriture [ColorFormat](../../com.aspose.slides/colorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)  

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}  
```
public final Color getAutomaticSeriesColor()
```

Renvoie une couleur automatique de série basée sur l’index de la série et le style du graphique. Cette couleur est utilisée par défaut si FillType est égal à NotDefined.

**Retour:**  
java.awt.Color - L’objet java.awt.Color.  

### getShowInnerPoints() {#getShowInnerPoints--}  
```
public final boolean getShowInnerPoints()
```

Représente les points internes. True si les points internes sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Retour:**  
boolean  

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}  
```
public final void setShowInnerPoints(boolean value)
```

Représente les points internes. True si les points internes sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}  
```
public final boolean getShowOutlierPoints()
```

Représente les points aberrants. True si les points aberrants sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Retour:**  
boolean  

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}  
```
public final void setShowOutlierPoints(boolean value)
```

Représente les points aberrants. True si les points aberrants sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}  
```
public final boolean getShowMeanMarkers()
```

Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Retour:**  
boolean  

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}  
```
public final void setShowMeanMarkers(boolean value)
```

Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}  
```
public final boolean getShowMeanLine()
```

Représente la ligne de moyenne. True si la ligne de moyenne est affichée sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Retour:**  
boolean  

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}  
```
public final void setShowMeanLine(boolean value)
```

Représente la ligne de moyenne. True si la ligne de moyenne est affichée sur le graphique BoxAndWhisker. S’applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}  
```
public final int getQuartileMethod()
```

Représente la méthode du quartile. S’applique uniquement aux graphiques BoxAndWhisker.

**Retour:**  
int  

### setQuartileMethod(int value) {#setQuartileMethod-int-}  
```
public final void setQuartileMethod(int value)
```

Représente la méthode du quartile. S’applique uniquement aux graphiques BoxAndWhisker.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}  
```
public final boolean getShowConnectorLines()
```

Représente les lignes de connexion. S’applique uniquement aux graphiques Waterfall.

**Retour:**  
boolean  

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}  
```
public final void setShowConnectorLines(boolean value)
```

Représente les lignes de connexion. S’applique uniquement aux graphiques Waterfall.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}  
```
public final int getParentLabelLayout()
```

Représente la disposition des étiquettes de catégorie parent. S’applique uniquement aux graphiques Treemap.

**Retour:**  
int  

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}  
```
public final void setParentLabelLayout(int value)
```

Représente la disposition des étiquettes de catégorie parent. S’applique uniquement aux graphiques Treemap.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}  
```
public final boolean hasUpDownBars()
```

Détermine si le graphique en ligne ou en actions possède des barres haut/bas. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.UpDownBars.HasUpDownBars en lecture/écriture pour modifier la valeur. Utilisez la propriété ParentSeriesGroup.UpDownBars pour formater les barres haut/bas. Lecture seule boolean.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retour:**  
boolean  

### getGapWidth() {#getGapWidth--}  
```
public final int getGapWidth()
```

Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.GapWidth en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.GapWidth.

**Retour:**  
int  

### getGapDepth() {#getGapDepth--}  
```
public final int getGapDepth()
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.GapDepth en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.GapDepth.

**Retour:**  
int  

### getFirstSliceAngle() {#getFirstSliceAngle--}  
```
public final int getFirstSliceAngle()
```

Spécifie l’angle de la première tranche du diagramme circulaire ou du diagramme anneau, en degrés (dans le sens des aiguilles d’une montre à partir du haut, de 0 à 360 degrés). Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.FirstSliceAngle en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.FirstSliceAngle.

**Retour:**  
int  

### getDoughnutHoleSize() {#getDoughnutHoleSize--}  
```
public final byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un diagramme anneau (peut être comprise entre 10 et 90 % de la taille de la zone de tracé). Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.DoughnutHoleSize en lecture/écriture pour modifier la valeur. Lecture seule byte.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.DoughnutHoleSize.

**Retour:**  
byte  

### getOverlap() {#getOverlap--}  
```
public final byte getOverlap()
```

Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent. C’est une projection de la propriété correspondante dans le groupe de séries parent, et donc cette propriété est en lecture seule. Pour modifier la valeur, utilisez la propriété ParentSeriesGroup.Overlap en lecture/écriture. Lecture seule byte.

--------------------

Overlap spécifie le degré de chevauchement ou d’espacement entre les barres et les colonnes en pourcentage de leur largeur : -100 % : espacement maximal (les barres sont complètement séparées). 0 % : les barres sont placées côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent complètement). Il s’agit d’une projection de la propriété ParentSeriesGroup.Overlap.

**Retour:**  
byte  

### getSecondPieSize() {#getSecondPieSize--}  
```
public final int getSecondPieSize()
```

Spécifie la taille de la seconde tranche ou de la seconde barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille de la première tranche (peut être comprise entre 5 et 200 %). Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.SecondPieSize en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.SecondPieSize.

**Retour:**  
int  

### hasSeriesLines() {#hasSeriesLines--}  
```
public final boolean hasSeriesLines()
```

Détermine s’il existe des lignes de série pour cette série et les séries apparentées. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.HasSeriesLines en lecture/écriture pour modifier la valeur. Utilisez la propriété ParentSeriesGroup.SeriesLinesFormat pour formater les lignes de série. Lecture seule boolean.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.HasSeriesLines.

**Retour:**  
boolean  

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}  
```
public final int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.BubbleSizeRepresentation en lecture/écriture pour modifier la valeur.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.BubbleSizeRepresentation.

**Retour:**  
int  

### getPieSplitPosition() {#getPieSplitPosition--}  
```
public final double getPieSplitPosition()
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la seconde tranche ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.PieSplitPosition en lecture/écriture pour modifier la valeur. Lecture seule double.

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.PieSplitPosition.

**Retour:**  
double  

### getPieSplitBy() {#getPieSplitBy--}  
```
public final int getPieSplitBy()
```

Spécifie comment déterminer quels points de données se trouvent dans la seconde tranche ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.PieSplitBy en lecture/écriture pour modifier la valeur. Lecture seule [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Il s’agit de la projection de la propriété ParentSeriesGroup.PieSplitBy. 2) Si la valeur de la propriété est PieSplitType.Custom, vous pouvez définir les informations de séparation personnalisées avec la propriété ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**  
int  

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}  
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de séparation personnalisées pour un graphique « pie-of-pie » ou « bar-of-pie » avec une séparation personnalisée. Contient les points de données qui doivent être dessinés dans la seconde tranche ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Cette propriété n’appartient pas seulement à cette série mais à toutes les séries du groupe de séries parent – il s’agit d’une projection de la propriété du groupe correspondante Lecture seule [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Il s’agit de la projection de la propriété ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  

### isColorVaried() {#isColorVaried--}  
```
public final boolean isColorVaried()
```
Spécifie que chaque marqueur de données de la série a une couleur différente. Cette propriété ne s’applique pas uniquement à cette série mais à toutes les séries du groupe de séries parent – il s’agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.IsColorVaried en lecture/écriture pour modifier la valeur. Lecture seule boolean.

Ceci est la projection de la propriété ParentSeriesGroup.IsColorVaried.

**Renvoie:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Spécifie le facteur d’échelle pour le graphique à bulles (peut être compris entre 0 et 300 % de la taille par défaut). Cette propriété ne s’applique pas uniquement à cette série mais à toutes les séries du groupe de séries parent – il s’agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.BubbleSizeScale en lecture/écriture pour modifier la valeur.

Ceci est la projection de la propriété ParentSeriesGroup.BubbleSizeScale.

**Renvoie:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d’un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d’un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation)