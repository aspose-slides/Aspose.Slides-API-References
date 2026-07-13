---
title: IChartDataPointCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van een seriedatapunt voor.
type: docs
url: /nl/com.aspose.slides/ichartdatapointcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Stelt een collectie van een seriedatapunt voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het seriedatapunt op basis van de index (het seriële nummer in deze collectie). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Retourneert de index (serienummer in deze collectie) van een datapunt in deze collectie. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het XValue-eigenschapobject van datapunten. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het XValue-eigenschapobject van datapunten. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het YValue-eigenschapobject van datapunten. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het YValue-eigenschapobject van datapunten. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het Value-eigenschapobject van datapunten. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het Value-eigenschapobject van datapunten. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specificeert het type waarden in de lijst met eigenschappen ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Als de collectie al een datapunt met index index bevat, retourneert deze het datapunt. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Retourneert het seriedatapunt op basis van de index (het seriële nummer in deze collectie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Retourneert de index (serienummer in deze collectie) van een datapunt in deze collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Retourneert:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het XValue-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.XValue.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het XValue-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.XValue.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceForYValues()
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het YValue-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.YValue.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het YValue-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.YValue.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.BubbleSize.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het BubbleSize-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPointEx.BubbleSize.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het Value-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPoint.Value.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retourneert:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk is in het Value-eigenschapobject van datapunten. Met andere woorden specificeert het type waarde van de eigenschap ChartDataPoint.Value.Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Specificeert het type waarden in de lijst met eigenschappen ChartDataPoint.ErrorBarsCustomValues. Alleen-lezen [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Retourneert:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Als de collectie al een datapunt met index index bevat, retourneert deze het datapunt. Als de collectie geen datapunt met index index==N bevat (wanneer het aantal datapunten in deze collectie kleiner of gelijk aan N is), dan worden er ontbrekende datapunten toegevoegd en wordt het laatste (dat de gevraagde index heeft) geretourneerd. Bijvoorbeeld, de collectie-indexen zijn {0, 1, 2} en de gevraagde index is 5. De methode voegt dan ontbrekende datapunten toe: {0, 1, 2, 3, 4, 5}. En retourneert het datapunt met index 5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | long | Index. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Retourneert het datapunt met de gevraagde index.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Stock-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Stock-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Line-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Line-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Scatter-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Radar-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Radar-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Column- of Bar-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) en ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Column- of Bar-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) en ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Area-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Area-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Pie-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Pie-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Doughnut-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Doughnut-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | double | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Bubble-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xValue | java.lang.String | Datapunt-X-waarde |
| yValue | double | Datapunt-Y-waarde |
| bubbleSize | double | Datapunt-BubbleSize |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType een van de Surface-subtypen is (zie ook de methode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Sunburst is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-SizeValue |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Waterfall is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType BoxAndWhisker is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Treemap is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-SizeValue |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Histogram is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Funnel is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapuntwaarde |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Maakt een nieuw datapunt aan en voegt het toe aan het einde van de collectie. Van toepassing op series waarvan chartType Map is.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datapunt-ColorValue |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nieuw datapunt.

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een datapunt dat verwijderd moet worden. |