---
title: ChartDataPointCollection
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente la collection d'un point de données de série.
type: docs
url: /fr/com.aspose.slides/chartdatapointcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Représente la collection d'un point de données de série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point de données de série par indice (son numéro de série dans cette collection). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Renvoie l'indice (numéro de série) du point de données dans cette collection. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété XValue des points de données. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété XValue des points de données. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété YValue des points de données. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété YValue des points de données. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété BubbleSize des points de données. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété BubbleSize des points de données. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété Value des points de données. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété Value des points de données. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Spécifie les types de valeurs dans la liste des propriétés ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Si la collection contient déjà un point de données avec l'indice index, alors renvoie ce point de données. |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copie vers le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'indice indiqué. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Renvoie le point de données de série par indice (son numéro de série dans cette collection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Renvoie l'indice (numéro de série) du point de données dans cette collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Renvoie :**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété XValue des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.XValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie :**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété XValue des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.XValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété YValue des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.YValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie :**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété YValue des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.YValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété BubbleSize des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.BubbleSize.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie :**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété BubbleSize des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.BubbleSize.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété Value des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.Value.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie :**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective dans l'objet de propriété Value des points de données. En d’autres termes, cela indique le type de valeur de la propriété ChartDataPoint.Value.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Spécifie les types de valeurs dans la liste des propriétés ChartDataPoint.ErrorBarsCustomValues. Lecture-seul [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Renvoie :**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Si la collection contient déjà un point de données avec l’indice index, alors renvoie ce point de données. Si la collection ne contient pas de point de données avec l’indice index==N (lorsque le nombre de points de données dans cette collection est inférieur ou égal à N), alors ajoute les points manquants et renvoie le dernier (celui qui a l’indice demandé). Par exemple, les indices de la collection sont {0, 1, 2} et l’indice demandé est 5. La méthode ajoute alors les points manquants : {0, 1, 2, 3, 4, 5}. Et renvoie le point de données d’indice 5.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | long | Indice. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Renvoie le point de données avec l’indice demandé.
### size() {#size--}
```
public final int size()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture-seul int.

**Renvoie :**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Copie vers le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau dans lequel copier. |
| arrayIndex | int | Indice de départ de la copie. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture-seul boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture-seul Object.

**Renvoie :**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un IGenericEnumerator utilisable pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator pour l'ensemble de la collection.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Stock (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Stock (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Radar (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Radar (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Column ou Bar (voir aussi les méthodes [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) et [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Column ou Bar (voir aussi les méthodes [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) et [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Area (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Area (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir aussi la méthode [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir aussi la méthode [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Doughnut (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Doughnut (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Surface (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Surface (voir aussi la méthode [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Sunburst.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Treemap.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est BoxAndWhisker.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Waterfall.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Histogram.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Funnel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chart type est Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### clear() {#clear--}
```
public final void clear()
```

Removes all elements from the collection.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)


Supprime l'élément à l'indice indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du point de données à supprimer. |