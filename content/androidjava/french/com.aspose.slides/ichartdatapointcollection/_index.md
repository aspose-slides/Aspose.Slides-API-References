---
title: IChartDataPointCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection d'un point de données de série.
type: docs
url: /fr/com.aspose.slides/ichartdatapointcollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Représente une collection d'un point de données de série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point de données de série par indice (son numéro de série dans cette collection). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Renvoie l'indice (numéro de série dans cette collection) du point de données dans cette collection. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété XValue des points de données. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété XValue des points de données. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété YValue des points de données. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété YValue des points de données. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété BubbleSize des points de données. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété BubbleSize des points de données. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété Value des points de données. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété Value des points de données. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Spécifie le type des valeurs dans la liste de propriétés ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Si la collection contient déjà un point de données avec l'indice index, alors renvoie ce point de données. |
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
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Crée le nouveau point de données et l'ajoute à la fin de la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'indice donné. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Renvoie le point de données de série par indice (son numéro de série dans cette collection).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```


Renvoie l'indice (numéro de série dans cette collection) du point de données dans cette collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Renvoie:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété XValue des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.XValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété XValue des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.XValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété YValue des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.YValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceForYValues(int value)
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété YValue des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.YValue.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété BubbleSize des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.BubbleSize.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété BubbleSize des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPointEx.BubbleSize.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété Value des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPoint.Value.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Renvoie:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```


Spécifie si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est réelle dans l'objet de la propriété Value des points de données. En d'autres termes, cela spécifie le type de valeur de la propriété ChartDataPoint.Value.Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```


Spécifie le type des valeurs dans la liste de propriétés ChartDataPoint.ErrorBarsCustomValues. Lecture seule [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Renvoie:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```


Si la collection contient déjà un point de données avec l'indice index, alors renvoie ce point de données. Si la collection ne contient pas de point de données avec index==N (lorsque le nombre de points de données dans cette collection est inférieur ou égal à N), alors ajoute les points manquants et renvoie le dernier (qui possède l'indice demandé). Par exemple, les indices de la collection sont {0, 1, 2}, et l'indice demandé est 5. La méthode ajoute alors les points manquants : {0, 1, 2, 3, 4, 5}. Et renvoie le point de données avec l'indice 5.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | long | Index. |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Renvoie le point de données avec l'indice demandé.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Stock (voir également la méthode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données. |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Stock (voir également la méthode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données. |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir également la méthode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données. |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir également la méthode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données. |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Scatter (voir également la méthode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Radar (voir également la méthode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Radar (voir également la méthode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Column ou Bar (voir également les méthodes ChartTypeCharacterizer.IsChartTypeColumn(ChartType) et ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Column ou Bar (voir également les méthodes ChartTypeCharacterizer.IsChartTypeColumn(ChartType) et ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Area (voir également la méthode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Area (voir également la méthode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir également la méthode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir également la méthode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Doughnut (voir également la méthode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Doughnut (voir également la méthode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | double | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Bubble (voir également la méthode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue du point de données |
| yValue | double | YValue du point de données |
| bubbleSize | double | BubbleSize du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Surface (voir également la méthode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Surface (voir également la méthode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Sunburst.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Waterfall.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est BoxAndWhisker.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Treemap.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Histogram.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Funnel.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valeur du point de données |

**Renvoie:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nouveau point de données.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le type de graphique est Map.

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
public abstract void clear()
```

Removes all elements from the collection.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)


Supprime l'élément à l'indice donné.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du point de données à supprimer. |