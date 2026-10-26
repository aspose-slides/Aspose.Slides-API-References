---
title: ChartDataPointCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Datenpunkten einer Serie dar.
type: docs
url: /de/com.aspose.slides/chartdatapointcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Stellt eine Sammlung von Seriendatenpunkten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Seriendatenpunkt anhand des Index zurück (seine Seriennummer in dieser Sammlung). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Gibt den Index (die Seriennummer) des Datenpunkts in dieser Sammlung zurück. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Gibt die Typen der Werte in der Eigenschaftsliste ChartDataPoint.ErrorBarsCustomValues an. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, wird dieser Datenpunkt zurückgegeben. |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Gibt den Seriendatenpunkt anhand des Index zurück (seine Seriennummer in dieser Sammlung).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Gibt den Index (die Seriennummer) des Datenpunkts in dieser Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Rückgabe:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.XValue.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im XValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.XValue.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.YValue.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im YValue-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.YValue.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.BubbleSize.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im BubbleSize-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.BubbleSize.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.Value.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Rückgabe:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Gibt an, ob die Eigenschaft AsCell oder AsLiteralString oder AsLiteralDouble im Value-Eigenschaftsobjekt der Datenpunkte tatsächlich ist. Mit anderen Worten gibt sie den Typ des Wertes der Eigenschaft ChartDataPoint.Value.Data an. Lese-/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Gibt die Typen der Werte in der Eigenschaftsliste ChartDataPoint.ErrorBarsCustomValues an. Nur-Lesen [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Rückgabe:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, wird dieser Datenpunkt zurückgegeben. Enthält die Sammlung keinen Datenpunkt mit dem Index index==N (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), werden fehlende Datenpunkte ergänzt und der letzte (mit dem angeforderten Index) zurückgegeben. Beispiel: Die Sammlungsindizes sind \{0, 1, 2\}, und der angeforderte Index ist 5. Die Methode fügt fehlende Datenpunkte hinzu: \{0, 1, 2, 3, 4, 5\} und gibt den Datenpunkt mit Index 5 zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | long | Index. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Gibt den Datenpunkt mit dem angeforderten Index zurück.
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur-Lesen int.

**Rückgabe:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopiert in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| arrayIndex | int | Index, an dem das Kopieren beginnt. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lesen boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisationsobjekt zurück. Nur-Lesen Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ein java.util.Iterator für die gesamte Sammlung.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Stock-Untersorten ist (siehe auch die Methode [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt-Wert. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts. |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Line-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts. |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Line-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts. |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue des Datenpunkts |
| yValue | double | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue des Datenpunkts |
| yValue | double | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Scatter-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue des Datenpunkts |
| yValue | double | YValue des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Radar-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Radar-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Column- oder Bar-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)- und [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-Methoden).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Column- oder Bar-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)- und [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-Methoden).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Area-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Area-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Pie-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Pie-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Doughnut-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Doughnut-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue des Datenpunkts |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue des Datenpunkts |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue des Datenpunkts |
| yValue | double | YValue des Datenpunkts |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue des Datenpunkts |
| yValue | double | YValue des Datenpunkts |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize des Datenpunkts |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Bubble-Untertypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt BubbleSize |

**Rückgabewert:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | double | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Bubble-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xValue | java.lang.String | Datenpunkt XValue |
| yValue | double | Datenpunkt YValue |
| bubbleSize | double | Datenpunkt BubbleSize |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Surface-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Surface-Subtypen ist (siehe auch [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)-Methode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Sunburst ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt SizeValue |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Treemap ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt SizeValue |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type BoxAndWhisker ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Waterfall ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Histogram ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Funnel ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datenpunkt Value |

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chart type Map ist.

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

**Rückgabewert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Neuer Datenpunkt.

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Der Wert. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Datenpunkts. |