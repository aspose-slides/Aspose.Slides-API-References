---
title: ChartSeries
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une série de graphique.
type: docs
url: /fr/com.aspose.slides/chartseries/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Représente une série de graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourne le graphique parent. |
| [getExplosion()](#getExplosion--) | La distance d’une tranche de diagramme circulaire ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre du diagramme circulaire. |
| [setExplosion(int value)](#setExplosion-int-) | La distance d’une tranche de diagramme circulaire ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre du diagramme circulaire. |
| [getSmooth()](#getSmooth--) | Représente le lissage de courbe. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Représente le lissage de courbe. |
| [getName()](#getName--) | Retourne le nom de la série. |
| [getDataPoints()](#getDataPoints--) | Renvoie la collection de points de données de cette série. |
| [getType()](#getType--) | Renvoie un type de cette série. |
| [setType(int value)](#setType-int-) | Renvoie un type de cette série. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si cette série est tracée sur l’axe secondaire. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indique si cette série est tracée sur l’axe secondaire. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Renvoie le format d’une série. |
| [getOrder()](#getOrder--) | Renvoie l’ordre d’une série. |
| [setOrder(int value)](#setOrder-int-) | Renvoie l’ordre d’une série. |
| [getLabels()](#getLabels--) | Renvoie les étiquettes d’une série. |
| [getTrendLines()](#getTrendLines--) | Collection de lignes de tendance de séries. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Représente les barres d’erreur d’une série avec direction X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Représente les barres d’erreur d’une série avec direction Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Représente l’entrée de légende liée à cette série en lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Spécifie la forme d’une série d’un diagramme à barres 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Spécifie la forme d’une série d’un diagramme à barres 3D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Spécifie l’inversion de la couleur unie pour la série. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Renvoie une couleur automatique de la série basée sur l’index de la série et le style du graphique. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Représente les points internes. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Représente les points internes. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Représente les points aberrants. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Représente les points aberrants. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Représente les repères de moyenne. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Représente les repères de moyenne. |
| [getShowMeanLine()](#getShowMeanLine--) | Représente la ligne de moyenne. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Représente la ligne de moyenne. |
| [getQuartileMethod()](#getQuartileMethod--) | Représente la méthode de quartile. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Représente la méthode de quartile. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Représente les lignes de connexion. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Représente les lignes de connexion. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Représente la disposition des étiquettes de catégorie parent. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Représente la disposition des étiquettes de catégorie parent. |
| [hasUpDownBars()](#hasUpDownBars--) | Détermine si le graphique en ligne ou en bourse possède des barres haut/bas. |
| [getGapWidth()](#getGapWidth--) | Spécifie l’espace entre les groupes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, exprimée en pourcentage de la largeur du repère, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Spécifie l’angle de la première tranche d’un diagramme circulaire ou en beignet, en degrés (dans le sens des aiguilles d’une montre depuis le haut, de 0 à 360 degrés). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un diagramme en beignet (peut être entre 10 % et 90 % de la taille de la zone de traçage). |
| [getOverlap()](#getOverlap--) | Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2D, exprimé en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille de la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie », exprimée en pourcentage de la taille du premier diagramme (peut être entre 5 % et 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Détermine s’il existe des lignes de séries pour cette série et les séries apparentées. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur utilisée pour déterminer quels points de données se trouvent dans la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données se trouvent dans la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisées pour un diagramme « pie-of-pie » ou « bar-of-pie » avec division personnalisée. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque repère de données de la série a une couleur différente. |
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

La distance d’une tranche de diagramme circulaire ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre du diagramme circulaire. Lecture/écriture int.

**Renvoie :**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

La distance d’une tranche de diagramme circulaire ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre du diagramme circulaire. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Représente le lissage de courbe. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Représente le lissage de courbe. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Retourne le nom de la série. Lecture seule [IStringChartValue](../../com.aspose.slides/istringchartvalue).

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

Renvoie les étiquettes d’une série. Lecture seule [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Renvoie :**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Collection de lignes de tendance de séries. Lecture seule [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Les lignes de tendance sont disponibles (pas null) pour les séries de données dans les graphiques 2D non empilés de type zone, barre, colonne, ligne, stock, xy (nuage de points) et bulles. Elles ne sont pas disponibles pour les séries de données dans tout type de graphique empilé ou 3D. Elles ne sont également pas disponibles pour les graphiques radar, circulaire, surface ou beignet.

**Renvoie :**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Représente les barres d’erreur d’une série avec direction X. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les barres d’erreur avec direction X sont disponibles pour les séries de type zone, barre, nuage de points et bulles. Pour tout autre type de graphique cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Renvoie :**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Représente les barres d’erreur d’une série avec direction Y. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les barres d’erreur avec direction Y sont disponibles pour les séries de type zone, barre, ligne, nuage de points et bulles. Pour tout autre type de graphique cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Renvoie :**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Représente l’entrée de légende liée à cette série en lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Spécifie la forme d’une série d’un diagramme à barres 3D. Changing of value of this property can cause to automatically changing Type of series. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Renvoie :**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Spécifie la forme d’une série d’un diagramme à barres 3D. Changing of value of this property can cause to automatically changing Type of series. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

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

Spécifie l’inversion de la couleur unie pour la série. To apply color setting set series format FillType to FillType.Solid. Lecture/écriture [ColorFormat](../../com.aspose.slides/colorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Renvoie une couleur automatique de la série basée sur l’index de la série et le style du graphique. This color is used by default if FillType equals NotDefined.

**Renvoie :**
java.lang.Integer - The java.lang.Integer object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Représente les points internes. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Représente les points internes. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Représente les points aberrants. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final boolean getShowOutlierPoints()
```

Représente les points aberrants. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Représente les repères de moyenne. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Représente les repères de moyenne. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Représente la ligne de moyenne. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Représente la ligne de moyenne. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Représente la méthode de quartile. Applies only to BoxAndWhisker charts.

**Renvoie :**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Représente la méthode de quartile. Applies only to BoxAndWhisker charts.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Représente les lignes de connexion. Applies only to Waterfall charts.

**Renvoie :**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Représente les lignes de connexion. Applies only to Waterfall charts.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Représente la disposition des étiquettes de catégorie parent. Applies only to Treemap charts.

**Renvoie :**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Représente la disposition des étiquettes de catégorie parent. Applies only to Treemap charts.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Détermine si le graphique en ligne ou en bourse possède des barres haut/bas. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Lecture seule boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Renvoie :**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Spécifie l’espace entre les groupes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Lecture seule int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**Renvoie :**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Renvoie ou définit la distance, exprimée en pourcentage de la largeur du repère, entre les séries de données dans un graphique 3D. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Lecture seule int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**Renvoie :**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Spécifie l’angle de la première tranche d’un diagramme circulaire ou en beignet, en degrés (dans le sens des aiguilles d’une montre depuis le haut, de 0 à 360 degrés). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Lecture seule int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**Renvoie :**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un diagramme en beignet (peut être entre 10 % et 90 % de la taille de la zone de traçage). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Lecture seule byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**Renvoie :**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2D, exprimé en pourcentage (de -100 % à 100 %). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Lecture seule byte.

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**Renvoie :**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Spécifie la taille de la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie », exprimée en pourcentage de la taille du premier diagramme (peut être entre 5 % et 200 %). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Lecture seule int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**Renvoie :**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Détermine s’il existe des lignes de séries pour cette série et les séries apparentées. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Lecture seule boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**Renvoie :**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**Renvoie :**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie ». Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Lecture seule double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**Renvoie :**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Spécifie comment déterminer quels points de données se trouvent dans la deuxième tranche ou barre d’un diagramme « pie-of-pie » ou « bar-of-pie ». This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Lecture seule [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**Renvoie :**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de division personnalisées pour un diagramme « pie-of-pie » ou « bar-of-pie » avec division personnalisée. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**Renvoie :**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Spécifie que chaque repère de données de la série a une couleur différente. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Lecture seule boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Renvoie :**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Spécifie le facteur d’échelle pour le graphique à bulles (peut être entre 0 % et 300 % de la taille par défaut). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Renvoie :**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d’un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d’un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)