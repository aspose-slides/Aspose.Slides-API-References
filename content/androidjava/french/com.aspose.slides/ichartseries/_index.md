---
title: IChartSeries
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une série de graphique.
type: docs
url: /fr/com.aspose.slides/ichartseries/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Représente une série de graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | La distance d'une part de tarte ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre de la tarte. |
| [setExplosion(int value)](#setExplosion-int-) | La distance d'une part de tarte ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre de la tarte. |
| [getSmooth()](#getSmooth--) | Représente le lissage de courbe. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Représente le lissage de courbe. |
| [getMarker()](#getMarker--) | Renvoie le marqueur de série. |
| [getBar3DShape()](#getBar3DShape--) | Spécifie la forme d'une série d'un diagramme à barres 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Spécifie la forme d'une série d'un diagramme à barres 3-D. |
| [getName()](#getName--) | Renvoie le nom de la série. |
| [getDataPoints()](#getDataPoints--) | Renvoie la collection de points de données de cette série. |
| [getType()](#getType--) | Renvoie un type de cette série. |
| [setType(int value)](#setType-int-) | Renvoie un type de cette série. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Renvoie le groupe parent de la série. |
| [getFormat()](#getFormat--) | Renvoie le format d'une série. |
| [getOrder()](#getOrder--) | Renvoie l'ordre d'une série. |
| [setOrder(int value)](#setOrder-int-) | Renvoie l'ordre d'une série. |
| [getLabels()](#getLabels--) | Renvoie les Labels d'une série. |
| [getTrendLines()](#getTrendLines--) | Collection de lignes de tendance de série Lecture seule [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Représente les ErrorBars d'une série avec direction X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Représente les ErrorBars d'une série avec direction Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si cette série est tracée sur le deuxième axe des valeurs. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indique si cette série est tracée sur le deuxième axe des valeurs. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Renvoie ou définit le format numérique des valeurs de la série. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Renvoie ou définit le format numérique des valeurs de la série. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Renvoie ou définit le format numérique des valeurs x de la série. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Renvoie ou définit le format numérique des valeurs x de la série. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Renvoie ou définit le format numérique des valeurs y de la série. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Renvoie ou définit le format numérique des valeurs y de la série. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Renvoie ou définit le format numérique des tailles de bulles de la série. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Renvoie ou définit le format numérique des tailles de bulles de la série. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Spécifie que la série en barres, colonnes ou bulles doit inverser ses couleurs si la valeur est négative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Spécifie que la série en barres, colonnes ou bulles doit inverser ses couleurs si la valeur est négative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Spécifie la couleur solide inversée pour la série. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Collection d'entrées de légende associées à cette série Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Renvoie une couleur automatique de série basée sur l'index de la série et le style du diagramme. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Représente les points intérieurs. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Représente les points intérieurs. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Représente les points aberrants. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Représente les points aberrants. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Représente les marqueurs de moyenne. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Représente les marqueurs de moyenne. |
| [getShowMeanLine()](#getShowMeanLine--) | Représente les marqueurs de moyenne. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Représente les marqueurs de moyenne. |
| [getQuartileMethod()](#getQuartileMethod--) | Représente la méthode de quartile. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Représente la méthode de quartile. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Représente les lignes de connexion. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Représente les lignes de connexion. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Représente la disposition des étiquettes de catégories parentes. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Représente la disposition des étiquettes de catégories parentes. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [hasUpDownBars()](#hasUpDownBars--) | Détermine si le diagramme en ligne ou en cours a des barres haut/bas. |
| [getGapWidth()](#getGapWidth--) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un diagramme 3D. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque marqueur de données dans la série a une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Détermine s'il existe des lignes de série pour cette série et les séries apparentées. |
| [getOverlap()](#getOverlap--) | Spécifie le pourcentage de chevauchement des barres et des colonnes sur les diagrammes 2-D (de –100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou d'un diagramme en anneau (peut être entre 10 et 90 % de la taille de la zone de tracé). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Spécifie l'angle du premier secteur d'un diagramme en tarte ou en anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisées pour un diagramme « pie-of-pie » ou « bar-of-pie » avec division personnalisée. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

La distance d'une part de tarte ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre de la tarte. Lecture/écriture int.

**Retour :**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

La distance d'une part de tarte ouverte du centre du diagramme circulaire est exprimée en pourcentage du diamètre de la tarte. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Représente le lissage de courbe. True si le lissage de courbe est activé pour le diagramme en ligne ou le diagramme à dispersion. S'applique uniquement aux diagrammes en ligne et à dispersion reliés par des lignes. Lecture/écriture boolean.

**Retour :**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Représente le lissage de courbe. True si le lissage de courbe est activé pour le diagramme en ligne ou le diagramme à dispersion. S'applique uniquement aux diagrammes en ligne et à dispersion reliés par des lignes. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Renvoie le marqueur de série. Lecture seule [IMarker](../../com.aspose.slides/imarker).

**Retour :**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Spécifie la forme d'une série d'un diagramme à barres 3-D. La modification de la valeur de cette propriété peut entraîner le changement automatique du Type de la série. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retour :**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Spécifie la forme d'une série d'un diagramme à barres 3-D. La modification de la valeur de cette propriété peut entraîner le changement automatique du Type de la série. Lecture/écriture [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Renvoie le nom de la série. Lecture seule [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retour :**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Renvoie la collection de points de données de cette série. Lecture seule [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retour :**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Renvoie un type de cette série. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Retour :**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Renvoie un type de cette série. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Renvoie le groupe parent de la série. Lecture seule [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Retour :**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Renvoie le format d'une série. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Retour :**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Renvoie l'ordre d'une série. Lecture/écriture int.

**Retour :**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Renvoie l'ordre d'une série. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Renvoie les Labels d'une série. Lecture seule [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Retour :**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Collection de lignes de tendance de série Lecture seule [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Retour :**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Représente les ErrorBars d'une série avec direction X. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les ErrorBars avec direction X sont disponibles pour les séries de type area, bar, scatter et bubble. Pour les autres types de diagrammes, cette propriété renvoie null (y compris les diagrammes 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retour :**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Représente les ErrorBars d'une série avec direction Y. Lecture seule [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Les ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. Pour les autres types de diagrammes, cette propriété renvoie null (y compris les diagrammes 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retour :**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indique si cette série est tracée sur le deuxième axe des valeurs. Lecture/écriture boolean.

**Retour :**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indique si cette série est tracée sur le deuxième axe des valeurs. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Renvoie ou définit le format numérique des valeurs de la série. Lecture/écriture String.

**Retour :**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Renvoie ou définit le format numérique des valeurs de la série. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Renvoie ou définit le format numérique des valeurs x de la série. Lecture/écriture String.

**Retour :**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Renvoie ou définit le format numérique des valeurs x de la série. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Renvoie ou définit le format numérique des valeurs y de la série. Lecture/écriture String.

**Retour :**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Renvoie ou définit le format numérique des valeurs y de la série. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Renvoie ou définit le format numérique des tailles de bulles de la série. Lecture/écriture String.

**Retour :**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Renvoie ou définit le format numérique des tailles de bulles de la série. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Spécifie que la série en barres, colonnes ou bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Retour :**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Spécifie que la série en barres, colonnes ou bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Spécifie la couleur solide inversée pour la série. Pour appliquer le paramètre de couleur, définissez le FillType de la série sur FillType.Solid. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Renvoie une couleur automatique de série basée sur l'index de la série et le style du diagramme. Cette couleur est utilisée par défaut si FillType est égal à NotDefined.

**Retour :**
java.lang.Integer - Automatic color of series java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Représente les points intérieurs. True si les points intérieurs sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Retour :**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Représente les points intérieurs. True si les points intérieurs sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Représente les points aberrants. True si les points aberrants sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Retour :**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Représente les points aberrants. True si les points aberrants sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Retour :**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Représente les marqueurs de moyenne. True si la ligne de moyenne est affichée sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Retour :**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Représente les marqueurs de moyenne. True si la ligne de moyenne est affichée sur le diagramme BoxAndWhisker. S'applique uniquement aux diagrammes BoxAndWhisker. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Représente la méthode de quartile. S'applique uniquement aux diagrammes BoxAndWhisker.

**Retour :**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Représente la méthode de quartile. S'applique uniquement aux diagrammes BoxAndWhisker.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Représente les lignes de connexion. S'applique uniquement aux diagrammes Waterfall.

**Retour :**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Représente les lignes de connexion. S'applique uniquement aux diagrammes Waterfall.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Représente la disposition des étiquettes de catégorie parentes. S'applique uniquement aux diagrammes Treemap.

**Retour :**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Représente la disposition des étiquettes de catégorie parentes. S'applique uniquement aux diagrammes Treemap.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.BubbleSizeScale pour modifier la valeur.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.BubbleSizeScale.

**Retour :**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Détermine si le diagramme en ligne ou en cours possède des barres haut/bas. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.UpDownBars.HasUpDownBars pour modifier la valeur. Utilisez la propriété ParentSeriesGroup.UpDownBars pour formater les barres haut/bas. Lecture seule boolean.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retour :**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.GapWidth pour modifier la valeur. Lecture seule int.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.GapWidth.

**Retour :**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un diagramme 3D. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.GapDepth pour modifier la valeur. Lecture seule int.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.GapDepth.

**Retour :**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Spécifie que chaque marqueur de données dans la série a une couleur différente. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.IsColorVaried pour modifier la valeur. Lecture seule boolean.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.IsColorVaried.

**Retour :**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Détermine s'il existe des lignes de série pour cette série et les séries apparentées. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.HasSeriesLines pour modifier la valeur. Utilisez ParentSeriesGroup.SeriesLinesFormat pour formater les lignes de série. Lecture seule boolean.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.HasSeriesLines.

**Retour :**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Spécifie le pourcentage de chevauchement des barres et des colonnes sur les diagrammes 2-D (de –100 % à 100 %). Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent. C’est une projection de la propriété appropriée du groupe parent et elle est en lecture seule. Pour modifier la valeur, utilisez la propriété ParentSeriesGroup.Overlap en lecture/écriture. Lecture seule byte.

--------------------

Overlap spécifie le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur : -100 % : espacement maximal (les barres sont complètement séparées). 0 % : les barres sont côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent complètement). Il s'agit d'une projection de la propriété ParentSeriesGroup.Overlap.

**Retour :**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Spécifie la taille du deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.SecondPieSize en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.SecondPieSize.

**Retour :**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Utilisée avec la propriété PieSplitBy. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.PieSplitPosition en lecture/écriture pour modifier la valeur. Lecture seule double.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitPosition.

**Retour :**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou barre d'un diagramme « pie-of-pie » ou « bar-of-pie ». Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.PieSplitBy en lecture/écriture pour modifier la valeur. Lecture seule [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitBy. 2) Si la valeur de la propriété est PieSplitType.Custom, vous pouvez définir des informations de division personnalisées avec la propriété ParentSeriesGroup.PieSplitCustomPoints.

**Retour :**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Spécifie la taille du trou d'un diagramme en anneau (peut être entre 10 et 90 % de la taille de la zone de tracé). Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.DoughnutHoleSize en lecture/écriture pour modifier la valeur. Lecture seule byte.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.DoughnutHoleSize.

**Retour :**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Spécifie l'angle du premier secteur d'un diagramme en tarte ou en anneau, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.FirstSliceAngle en lecture/écriture pour modifier la valeur. Lecture seule int.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.FirstSliceAngle.

**Retour :**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de division personnalisées pour un diagramme « pie-of-pie » ou « bar-of-pie » avec division personnalisée. Contient les points de données qui doivent être affichés dans le deuxième secteur ou barre. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié Lecture seule [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitCustomPoints.

**Retour :**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. Cette propriété concerne non seulement cette série mais toutes les séries du groupe parent – il s'agit d'une projection de la propriété du groupe approprié. Cette propriété est donc en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe parent. Utilisez ParentSeriesGroup.BubbleSizeRepresentation en lecture/écriture pour modifier la valeur.

--------------------

Il s'agit de la projection de la propriété ParentSeriesGroup.BubbleSizeRepresentation.

**Retour :**
int