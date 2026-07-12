---
title: IChartDataPointCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Datenpunkten einer Serie dar.
type: docs
url: /de/com.aspose.slides/ichartdatapointcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Stellt eine Sammlung von Datenpunkten einer Serie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Datenpunkt der Serie anhand des Index zurück (seine Seriennummer in dieser Sammlung). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Gibt den Index (Seriennummer in dieser Sammlung) des Datenpunkts in dieser Sammlung zurück. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Gibt den Typ der Werte in der ChartDataPoint.ErrorBarsCustomValues-Eigenschaftsliste an. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, wird dieser Datenpunkt zurückgegeben. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Gibt den Datenpunkt der Serie anhand des Index zurück (seine Seriennummer in dieser Sammlung).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Gibt den Index (Seriennummer in dieser Sammlung) des Datenpunkts in dieser Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Rückgabe:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.XValue.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.XValue.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.YValue.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.YValue.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.BubbleSize.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPointEx.BubbleSize.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPoint.Value.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt des Datenpunkts tatsächlich ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft ChartDataPoint.Value.Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Gibt den Typ der Werte in der ChartDataPoint.ErrorBarsCustomValues-Eigenschaftsliste an. Nur-Lesen [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Rückgabe:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, wird dieser Datenpunkt zurückgegeben. Wenn die Sammlung keinen Datenpunkt mit dem Index index==N enthält (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), werden fehlende Datenpunkte hinzugefügt und der letzte (der den gewünschten Index hat) zurückgegeben. Beispiel: Sammlungsindizes sind \{0, 1, 2\} und der angeforderte Index ist 5. Dann fügt die Methode fehlende Datenpunkte hinzu: \{0, 1, 2, 3, 4, 5\}. Und gibt den Datenpunkt mit Index 5 zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | long | Index. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Gibt den Datenpunkt mit dem angeforderten Index zurück.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Line-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Line-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Radar-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Radar-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Column- oder Bar-Untertypen ist (siehe auch die Methoden ChartTypeCharacterizer.IsChartTypeColumn(ChartType) und ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Column- oder Bar-Untertypen ist (siehe auch die Methoden ChartTypeCharacterizer.IsChartTypeColumn(ChartType) und ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Area-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Area-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Pie-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Pie-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Doughnut-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Doughnut-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Surface-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Surface-Untertypen ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Sunburst ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt SizeValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Waterfall ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType BoxAndWhisker ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Treemap ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt SizeValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Histogram ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Funnel ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunktwert |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Erstellt einen neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType Map ist.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt ColorValue |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Der Wert. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Datenpunkts. |