---
title: ChartDataPointCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A sorozat adatpontjainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/chartdatapointcollection/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

A sorozat adatpontjainak gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a sorozat adatpontot az index alapján (a sorozat sorszámát ebben a gyűjteményben). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Visszaadja a data point indexét (sorszámát) ebben a gyűjteményben. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points XValue tulajdonság objektumban. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points XValue tulajdonság objektumban. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points YValue tulajdonság objektumban. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points YValue tulajdonság objektumban. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points BubbleSize tulajdonság objektumban. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points BubbleSize tulajdonság objektumban. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points Value tulajdonság objektumban. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points Value tulajdonság objektumban. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Megadja az értékek típusait a ChartDataPoint.ErrorBarsCustomValues tulajdonságlista elemeiben. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Ha a gyűjtemény már tartalmazza az adott indexű data point-ot, akkor visszaadja azt a data point-ot. |
| [size()](#size--) | Lekéri a ténylegesen a gyűjteményben lévő elemek számát. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Másolás a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterator-t az egész gyűjteményhez. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új data point-ot és a gyűjtemény végére adja. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az adott indexű elemet. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Visszaadja a sorozat adatpontot az index alapján (a sorozat sorszámát ebben a gyűjteményben).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```


Visszaadja a data point indexét (sorszámát) ebben a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Visszatér:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points XValue tulajdonság objektumban. Más szóval a ChartDataPoint.XValue.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatér:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points XValue tulajdonság objektumban. Más szóval a ChartDataPoint.XValue.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceForYValues--}
```
public final int getDataSourceTypeForYValues()
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points YValue tulajdonság objektumban. Más szóval a ChartDataPoint.YValue.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatér:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points YValue tulajdonság objektumban. Más szóval a ChartDataPoint.YValue.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points BubbleSize tulajdonság objektumban. Más szóval a ChartDataPoint.BubbleSize.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatér:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points BubbleSize tulajdonság objektumban. Más szóval a ChartDataPoint.BubbleSize.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points Value tulajdonság objektumban. Más szóval a ChartDataPoint.Value.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatér:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```


Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság aktuális-e a data points Value tulajdonság objektumban. Más szóval a ChartDataPoint.Value.Data tulajdonság értéktípusát adja meg. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```


Megadja a ChartDataPoint.ErrorBarsCustomValues tulajdonságlista elemeinek értéktípusait. Csak olvasható [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Visszatér:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```


Ha a gyűjtemény már tartalmazza az adott indexű data point-ot, akkor visszaadja azt a data point-ot. Ha a gyűjtemény nem tartalmaz indexet index==N (ahol a data point-ok száma kisebb vagy egyenlő N-nel), akkor hiányzó data point-okat ad hozzá, és a legutóbb hozzáadott (a kért indexű) elemet adja vissza. Például, ha a gyűjtemény indexei \{0, 1, 2\}, a kért index 5, akkor a metódus a hiányzó elemeket adja hozzá: \{0, 1, 2, 3, 4, 5\}, és visszaadja az 5-ös indexű data point-ot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | long | Index. |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – visszaadja a kért indexű data point-ot.
### size() {#size--}
```
public final int size()
```


Lekéri a ténylegesen a gyűjteményben lévő elemek számát. Csak olvasható int.

**Visszatér:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Másolás a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | A tömb, amelybe másolni kell. |
| arrayIndex | int | Az index, ahonnan a másolás kezdődik. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – egy IGenericEnumerator, amely a gyűjtemény bejárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Visszaad egy java iterator-t az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – egy java.util.Iterator az egész gyűjteményhez.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Stock alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték. |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Stock alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték. |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Line alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték. |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Line alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték. |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Scatter alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Radar alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Radar alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Column vagy Bar alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) és [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Column vagy Bar alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) és [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja az Area alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja az Area alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Pie alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Pie alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Doughnut alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Doughnut alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Bubble alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Surface alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chartType-ja a Surface alttípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Sunburst.

**Paraméterek::
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IBox  ... (…)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Treemap.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a BoxAndWhisker.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Waterfall.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Histogram.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Funnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point érték |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Létrehozza az új data point-ot és a gyűjtemény végére adja. Alkalmazható sorozatokra, amelyek chart type-ja a Map.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**Visszatér:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – új data point.
### clear() {#clear--}
```
public final void clear()
```


Eltávolítja a gyűjtemény összes elemét.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```


Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Az érték. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja az adott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő data point indexe. |