---
title: ChartDataPointCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av datapunkter i en serie.
type: docs
url: /sv/com.aspose.slides/chartdatapointcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Representerar en samling av en serie-datapunkt.
## Metoder

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar serie-datapunkten efter index (dess serienummer i denna samling). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Returnerar index (serienummer) för datapunkten i denna samling. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens XValue-egenskapsobjekt. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens XValue-egenskapsobjekt. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens YValue-egenskapsobjekt. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens YValue-egenskapsobjekt. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens BubbleSize-egenskapsobjekt. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens BubbleSize-egenskapsobjekt. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens Value-egenskapsobjekt. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens Value-egenskapsobjekt. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Anger typer av värden i ChartDataPoint.ErrorBarsCustomValues-egenskapslistan. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Om samlingen redan innehåller en datapunkt med index index returneras denna datapunkt. |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar till angiven array. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomsten till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Skapar en ny datapunkt och lägger till den i slutet av samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Tar bort det angivna värdet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Returnerar serie-datapunkten efter index (dess serienummer i denna samling).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Returnerar index (serienummer) för datapunkten i denna samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Returnerar:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens XValue-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.XValue.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returnerar:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens XValue-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.XValue.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens YValue-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.YValue.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returnerar:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens YValue-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.YValue.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens BubbleSize-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.BubbleSize.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returnerar:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens BubbleSize-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.BubbleSize.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens Value-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.Value.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returnerar:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktiv i datapunktens Value-egenskapsobjekt. Med andra ord anger den vilken typ av värde som ChartDataPoint.Value.Data-egenskapen har. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Anger typer av värden i ChartDataPoint.ErrorBarsCustomValues-egenskapslistan. Skrivskyddad [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Returnerar:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Om samlingen redan innehåller en datapunkt med index index returneras denna datapunkt. Om samlingen inte innehåller en datapunkt med index index==N (när antalet datapunkter i denna samling är mindre än eller lika med N) läggs saknade datapunkter till och den sista (som har begärt index) returneras. Till exempel, samlingens index är {0, 1, 2}, och begärt index är 5. Då lägger metoden till saknade datapunkter: {0, 1, 2, 3, 4, 5}. Och returnerar datapunkten med index 5.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | long | Index. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Returnerar datapunkten med begärt index.

### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopierar till angiven array.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array att kopiera till. |
| arrayIndex | int | Index att börja kopiera från. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomsten till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Skapar en ny datapunkt och lägger till den i slutet av samlingen. Gäller för serier vars diagramtyp är en av Stock-undertyperna (se även [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)-metoden).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Stock-undertyperna (se även [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Line-undertyperna (se även [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Line-undertyperna (se även [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens XValue |
| yValue | double | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunktens XValue |
| yValue | double | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Scatter-undertyperna (se även [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunktens XValue |
| yValue | double | Datapunktens YValue |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Radar-undertyperna (se även [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Radar-undertyperna (se även [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Column- eller Bar-undertyperna (se även [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) och [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Column- eller Bar-undertyperna (se även [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) och [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Area-undertyperna (se även [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Area-undertyperna (se även [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Pie-undertyperna (se även [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Pie-undertyperna (se även [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Doughnut-undertyperna (se även [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Doughnut-undertyperna (se även [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktens Value |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens BubbleSize |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens BubbleSize |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunktens XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens BubbleSize |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens XValue |
| yValue | double | Datapunktens YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens BubbleSize |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunktens XValue |
| yValue | double | Datapunktens YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktens BubbleSize |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-undertyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Bubble-subtyperna (se även [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Surface-subtyperna (se även [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Surface-subtyperna (se även [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metod).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Sunburst.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt SizeValue |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Treemap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt SizeValue |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är BoxAndWhisker.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Waterfall.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Histogram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Funnel.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt Value |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chart type är Map.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt ColorValue |

**Returnerar:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla element från samlingen.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Värdet. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en datapunkt som ska tas bort. |