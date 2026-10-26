---
title: ChartDataPointCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van een serie gegevenspunt voor.
type: docs
url: /nl/com.aspose.slides/chartdatapointcollection/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Stelt een collectie van een series gegevenspunt voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het series-gegevenspunt op basis van de index (het serienummer in deze collectie). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Retourneer index (serienummer) van gegevenspunt in deze collectie. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten XValue property object. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten XValue property object. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten YValue property object. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten YValue property object. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten BubbleSize property object. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten BubbleSize property object. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten Value property object. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten Value property object. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specificeert types van waarden in ChartDataPoint.ErrorBarsCustomValues properties lijst. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Als de collectie al een gegevenspunt met index index bevat, retourneert dit gegevenspunt. |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieer naar opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Retourneert het series-gegevenspunt op basis van de index (het serienummer in deze collectie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Retourneer index (serienummer) van gegevenspunt in deze collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Retourneert:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten XValue property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.XValue.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten XValue property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.XValue.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten YValue property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.YValue.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten YValue property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.YValue.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten BubbleSize property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.BubbleSize.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten BubbleSize property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.BubbleSize.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten Value property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.Value.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap daadwerkelijk is in gegevenspunten Value property object. Met andere woorden, het specificeert het type waarde van ChartDataPoint.Value.Data eigendom. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Specificeert types van waarden in ChartDataPoint.ErrorBarsCustomValues properties lijst. Alleen-lezen [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Retourneert:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Als de collectie al een gegevenspunt met index index bevat, retourneert dit gegevenspunt. Als de collectie geen gegevenspunt met index index==N bevat (wanneer het aantal gegevenspunten in deze collectie kleiner of gelijk is aan N), worden de ontbrekende gegevenspunten toegevoegd en wordt het laatste (met de gevraagde index) geretourneerd. Bijvoorbeeld, collecties hebben indexen \{0, 1, 2\}, en de gevraagde index is 5. Dan voegt de methode ontbrekende gegevenspunten toe: \{0, 1, 2, 3, 4, 5\}. En retourneert het gegevenspunt met index 5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | long | Index. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Retourneert gegevenspunt met gevraagde index.
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retourneert:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopieer naar opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array om naar te kopiëren. |
| arrayIndex | int | Index om te beginnen met kopiëren. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Retourneert een java iterator voor de gehele collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een java.util.Iterator voor de gehele collectie.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Stock-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspuntwaarde. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Stock-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Line-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Line-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van het gegevenspunt |
| yValue | double | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | X-waarde van het gegevenspunt |
| yValue | double | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van het gegevenspunt |
| yValue | double | Y-waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Radar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Radar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Column- of Bar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) en [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Column- of Bar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) en [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Area-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Area-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Pie-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Pie-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Doughnut-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Doughnut-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Waarde van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Bubble-grootte van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Bubble-grootte van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van het gegevenspunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van het gegevenspunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Bubble-grootte van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van het gegevenspunt |
| yValue | double | Y-waarde van het gegevenspunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Bubble-grootte van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | X-waarde van het gegevenspunt |
| yValue | double | Y-waarde van het gegevenspunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Bubble-grootte van het gegevenspunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType één van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-methode).
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Gegevenspunt XValue |
| yValue | double | Gegevenspunt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Gegevenspunt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Gegevenspunt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt XValue |
| yValue | double | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Gegevenspunt XValue |
| yValue | double | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Gegevenspunt XValue |
| yValue | double | Gegevenspunt YValue |
| bubbleSize | double | Gegevenspunt BubbleSize |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypen is (zie ook [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Sunburst is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt SizeValue |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Treemap is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt SizeValue |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type BoxAndWhisker is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Waterfall is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Histogram is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Funnel is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt Value |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Maakt het nieuwe gegevenspunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chart type Map is.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Gegevenspunt ColorValue |

**Retour:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw gegevenspunt.

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een te verwijderen gegevenspunt. |