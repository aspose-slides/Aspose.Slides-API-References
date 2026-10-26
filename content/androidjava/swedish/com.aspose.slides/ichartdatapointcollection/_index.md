---
title: IChartDataPointCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av en seriedatapunkt.
type: docs
url: /sv/com.aspose.slides/ichartdatapointcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Representerar en samling av en series datapunkt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar series datapunkten efter index (dess serienummer i denna samling). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Returnerar index (serienummer i denna samling) för datapunkten i denna samling. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas XValue-egenskapsobjekt. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas XValue-egenskapsobjekt. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas YValue-egenskapsobjekt. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas YValue-egenskapsobjekt. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas BubbleSize-egenskapsobjekt. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas BubbleSize-egenskapsobjekt. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas Value-egenskapsobjekt. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas Value-egenskapsobjekt. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Anger typen av värden i listan av egenskaper ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Om samlingen redan innehåller en datapunkt med index index returneras denna datapunkt. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Skapar den nya datapunkten och lägger till den i slutet av samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Tar bort det angivna värdet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Returnerar series datapunkten efter index (dess serienummer i denna samling).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Returnerar index (serienummer i denna samling) för datapunkten i denna samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Returvärde:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas XValue-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returvärde:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceForXValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas XValue-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas YValue-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returvärde:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas YValue-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas BubbleSize-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returvärde:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas BubbleSize-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas Value-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returvärde:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Anger om AsCell- eller AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i datapunkternas Value-egenskapsobjekt. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Anger typen av värden i listan av egenskaper ChartDataPoint.ErrorBarsCustomValues. Endast läsning [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Returvärde:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Om samlingen redan innehåller en datapunkt med index index returneras denna datapunkt. Om samlingen inte innehåller en datapunkt med index index==N (när antalet datapunkter i denna samling är mindre än eller lika med N) läggs saknade datapunkter till och den sista (med önskat index) returneras. Till exempel är samlingens index {0, 1, 2} och det begärda indexet är 5. Då lägger metoden till saknade datapunkter: {0, 1, 2, 3, 4, 5}. Och returnerar datapunkten med index 5.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | long | Index. |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Returnerar datapunkt med begärt index.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Stock-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde. |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Stock-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde. |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Line-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde. |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Line-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde. |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | double | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | double | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Scatter-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | double | Datapunkt YValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Radar-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Radar-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Column- eller Bar-undertyperna (se även metoderna ChartTypeCharacterizer.IsChartTypeColumn(ChartType) och ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Column- eller Bar-undertyperna (se även metoderna ChartTypeCharacterizer.IsChartTypeColumn(ChartType) och ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Area-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Area-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Pie-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Pie-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Doughnut-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Doughnut-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | double | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Bubble-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xValue | java.lang.String | Datapunkt XValue |
| yValue | double | Datapunkt YValue |
| bubbleSize | double | Datapunkt BubbleSize |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Surface-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Surface-undertyperna (se även metoden ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Sunburst.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt SizeValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Waterfall.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp BoxAndWhisker.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Treemap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunkt SizeValue |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Histogram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Funnel.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunktvärde |

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier med diagramtyp Map.

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

**Returvärde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ny datapunkt.

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Värdet. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en datapunkt att ta bort. |