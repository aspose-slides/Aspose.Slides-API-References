---
title: IChartDataPointCollection
second_title: Aspose.Slides Java API referencia
description: A sorozat adatpontjainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ichartdatapointcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

A sorozat adatpontjainak gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a sorozat adatpontját az index (a gyűjteményben betöltött sorszám) alapján. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Visszaadja az adatpont indexét (a gyűjteményben betöltött sorszámát). |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok XValue tulajdonságobjektumában. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok XValue tulajdonságobjektumában. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok YValue tulajdonságobjektumában. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok YValue tulajdonságobjektumában. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok BubbleSize tulajdonságobjektumában. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok BubbleSize tulajdonságobjektumában. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok Value tulajdonságobjektumában. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e az adatpontok Value tulajdonságobjektumában. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Megadja az értékek típusát a ChartDataPoint.ErrorBarsCustomValues tulajdonságlistában. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Ha a gyűjtemény már tartalmaz adatpontot az index index-szel, akkor visszaadja ezt az adatpontot. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az adott indexű elemet. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Visszaadja a sorozat adatpontját az index (a gyűjteményben betöltött sorszám) alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Visszaadja az adatpont indexét (a gyűjteményben betöltött sorszámát).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Visszatérési érték:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok XValue tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.XValue.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok XValue tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.XValue.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok YValue tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.YValue.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok YValue tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.YValue.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok BubbleSize tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.BubbleSize.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok BubbleSize tulajdonságobjektumban. Más szóval meghatározza a ChartDataPointEx.BubbleSize.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok Value tulajdonságobjektumban. Más szóval meghatározza a ChartDataPoint.Value.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e a data pontok Value tulajdonságobjektumban. Más szóval meghatározza a ChartDataPoint.Value.Data értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Megadja a ChartDataPoint.ErrorBarsCustomValues tulajdonságlista értékeinek típusát. Csak olvasható [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Visszatérési érték:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Ha a gyűjtemény már tartalmaz adatpontot az index index-szel, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot az index index==N (ahol N a gyűjteményben lévő adatpontok száma, amely kisebb vagy egyenlő N-nel), akkor hiányzó adatpontokat ad hozzá, és az utolsót (amely a kért indexet tartalmazza) adja vissza. Például, ha a gyűjtemény indexei \{0, 1, 2\}, a kért index 5, akkor a metódus hozzáadja a hiányzó adatpontokat: \{0, 1, 2, 3, 4, 5\}, majd visszaadja a 5-ös indexű adatpontot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | long | Index. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Visszaadja a kért indexű adatpontot.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. Alkalmazható azokban a sorozatokban, amelyek chartType értéke a Stock altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeStock(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. Alkalmazható azokban a sorozatokban, amelyek chartType értéke a Stock altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeStock(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. Alkalmazható azokban a sorozatokban, amelyek chartType értéke a Line altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeLine(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. Alkalmazható azokban a sorozatokban, amelyek chartType értéke a Line altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeLine(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont értéke. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja. Alkalmazható azokban a sorozatokban, amelyek chartType értéke a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
|
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Scatter altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Radar altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeRadar(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Radar altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeRadar(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Column vagy Bar altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeColumn(ChartType) és a ChartTypeCharacterizer.IsChartTypeBar(ChartType) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Column vagy Bar altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeColumn(ChartType) és a ChartTypeCharacterizer.IsChartTypeBar(ChartType) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja az Area altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeArea(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja az Area altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeArea(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Pie altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypePie(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Pie altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypePie(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Doughnut altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Doughnut altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorokra, amelyek chartType-ja a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Bubble altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Surface altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Surface altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Sunburst.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont SizeValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Waterfall.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont érték |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa BoxAndWhisker.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Treemap.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont SizeValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Histogram.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont érték |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Funnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont érték |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagram típusa Map.

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
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataCell-}
```
public abstract void remove(IChartDataPoint value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Az érték. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó adatpont indexe. |