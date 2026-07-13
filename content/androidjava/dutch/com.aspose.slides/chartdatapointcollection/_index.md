---
title: ChartDataPointCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een collectie van een seriedatapunt.
type: docs
url: /nl/com.aspose.slides/chartdatapointcollection/
---
**Erfelijkheid:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Vertegenwoordigt een collectie van een seriedatapunt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het seriedatapunt op index (het seriële nummer in deze collectie). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Retourneert index (serienummer) van datapunt in deze collectie. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het XValue-eigenschapobject van datapunten. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het XValue-eigenschapobject van datapunten. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het YValue-eigenschapobject van datapunten. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het YValue-eigenschapobject van datapunten. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het Value-eigenschapobject van datapunten. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het Value-eigenschapobject van datapunten. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specificeert typen van waarden in de lijst met eigenschappen ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Als de collectie al een datapunt met index index bevat, retourneert dit datapunt. |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieer naar opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatieroot. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Retourneert het seriedatapunt op index (het seriële nummer in deze collectie).

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

Retourneert index (serienummer) van datapunt in deze collectie.

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

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het XValue-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.XValue.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het XValue-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.XValue.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het YValue-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.YValue.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceForYValues(int value)
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het YValue-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.YValue.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.BubbleSize.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.BubbleSize.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het Value-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.Value.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Specificeert of de eigenschap AsCell of AsLiteralString of AsLiteralDouble daadwerkelijk is in het Value-eigenschapobject van datapunten. Met andere woorden geeft het type waarde van ChartDataPoint.Value.Data weer. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Specificeert typen van waarden in de lijst met eigenschappen ChartDataPoint.ErrorBarsCustomValues. Alleen-lezen [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Retourneert:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Als de collectie al een datapunt met index index bevat, wordt dit datapunt geretourneerd. Als de collectie geen datapunt met index index==N bevat (wanneer het aantal datapunten in deze collectie minder of gelijk is aan N), dan worden missende datapunten toegevoegd en wordt het laatste (met de gevraagde index) geretourneerd. Bijvoorbeeld, de collectie-indices zijn \{0, 1, 2\}, en de gevraagde index is 5. Vervolgens voegt de methode missende datapunten toe: \{0, 1, 2, 3, 4, 5\}. En retourneert het datapunt met index 5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | long | Index. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Retourneert datapunt met gevraagde index.
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

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
| array | com.aspose.ms.System.Array | Array om naartoe te kopiëren. |
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

Retourneert een synchronisatieroot. Alleen-lezen Object.

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

Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een java.util.Iterator voor de volledige collectie.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Stock-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Stock-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Line-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Line-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Radar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Radar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Column- of Bar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) en [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Column- of Bar-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) en [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Area-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Area-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Pie-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Pie-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Doughnut-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Doughnut-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | X-waarde van datapunt |
| yValue | double | Y-waarde van datapunt |
| bubbleSize | double | BubbleSize-waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypes is (zie ook [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) methode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Sunburst is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Treemap is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype BoxAndWhisker is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Waterfall is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Histogram is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Funnel is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Waarde van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Creëert het nieuwe datapunt en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan charttype Map is.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue van datapunt |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.
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
| index | int | Index van een datapunt om te verwijderen. |