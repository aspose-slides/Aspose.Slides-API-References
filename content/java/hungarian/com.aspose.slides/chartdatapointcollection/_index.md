---
title: ChartDataPointCollection
second_title: Aspose.Slides for Java API referencia
description: Egy sorozathoz tartozó adatpontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/chartdatapointcollection/
---
**Öröklés:**
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
| [get_Item(int index)](#get-Item-int-) | Visszaadja a sorozat adatpontját az index alapján (a gyűjteményben lévő sorszám). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Visszaadja az adatpont indexét (sorszámát) a gyűjteményben. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok XValue tulajdonságobjektumában. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok XValue tulajdonságobjektumában. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok YValue tulajdonságobjektumában. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok YValue tulajdonságobjektumában. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok BubbleSize tulajdonságobjektumában. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok BubbleSize tulajdonságobjektumában. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok Value tulajdonságobjektumában. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok Value tulajdonságobjektumában. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Megadja az értékek típusát a ChartDataPoint.ErrorBarsCustomValues tulajdonságlistában. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Ha a gyűjtemény már tartalmaz adatpontot a megadott indexszel, akkor visszaadja ezt az adatpontot. |
| [size()](#size--) | Visszaadja a gyűjteményben ténylegesen lévő elemek számát. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Másolás a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexnél. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Visszaadja a sorozat adatpontját az index alapján (a gyűjteményben lévő sorszám).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Visszaadja az adatpont indexét (sorszámát) a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Visszatérési érték:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok XValue tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.XValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok XValue tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.XValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok YValue tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.YValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok YValue tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.YValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok BubbleSize tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.BubbleSize.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceForBubbleSizes(int value)
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok BubbleSize tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.BubbleSize.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok Value tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.Value.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az adatpontok Value tulajdonságobjektumában. Más szóval megadja a ChartDataPoint.Value.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Megadja a ChartDataPoint.ErrorBarsCustomValues tulajdonságlistában lévő értékek típusát. Csak olvasás [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Visszatérési érték:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Ha a gyűjtemény már tartalmaz adatpontot a megadott indexszel, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot az index==N esetén (amikor a gyűjteményben lévő adatpontok száma kisebb vagy egyenlő N-nél), akkor hiányzó adatpontokat ad hozzá, és visszaadja az utolsót (amelyiknek a kért indexe van). Például a gyűjtemény indexei {0, 1, 2}, és a kért index 5. Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5-ös indexű adatpontot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | long | Index. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Visszaadja a kért indexű adatpontot.

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasás int.

**Visszatérési érték:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Másolás a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | A másolandó tömb. |
| arrayIndex | int | Az index, ahonnan a másolás kezdődik. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasás boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasás Object.

**Visszatérési érték:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Egy IGenericEnumerator, amely a gyűjteményen iterál.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Egy java.util.Iterator a teljes gyűjteményhez.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és hozzáadja a gyűjtemény végéhez. Alkalmazható sorozatokra, amelyek chartType-ja a Stock altípusok egyike (lásd még a [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Stock altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Line altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Line altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont X értéke |
| yValue | double | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Az adatpont X értéke |
| yValue | double | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Scatter altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Az adatpont X értéke |
| yValue | double | Az adatpont Y értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Radar altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Radar altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Column vagy Bar altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) és [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Column vagy Bar altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) és [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke az Area altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke az Area altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Pie altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Pie altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Doughnut altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Doughnut altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Az adatpont értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont BubbleSize értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont BubbleSize értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Az adatpont X értéke |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont Y értéke |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont BubbleSize értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont X értéke |
| yValue | double | Az adatpont Y értéke |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont BubbleSize értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Az adatpont X értéke |
| yValue | double | Az adatpont Y értéke |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az adatpont BubbleSize értéke |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| 
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | double | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Surface altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType értéke a Surface altípusok egyike (lásd még [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metódus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Sunburst.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont SizeValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Treemap.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont SizeValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa BoxAndWhisker.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Waterfall.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Histogram.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Funnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható sorokra, amelyek diagramtípusa Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont ColorValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

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
| index | int | A törlendő adatpont indexe. |