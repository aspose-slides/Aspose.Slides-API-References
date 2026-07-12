---
title: IChartDataPointCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
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

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a sorozat adatpontot az index alapján (a gyűjteményben lévő sorozatszáma). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Visszaadja a sorozat adatpont indexét (a gyűjteményben lévő sorozatszámát). |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok XValue tulajdonság objektumában. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok XValue tulajdonság objektumában. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok YValue tulajdonság objektumában. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok YValue tulajdonság objektumában. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok BubbleSize tulajdonság objektumában. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok BubbleSize tulajdonság objektumában. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok Value tulajdonság objektumában. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok Value tulajdonság objektumában. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Megadja az értékek típusát a ChartDataPoint.ErrorBarsCustomValues tulajdonságlistában. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Ha a gyűjtemény már tartalmaz adatpontot az index index-szel, akkor visszaadja ezt az adatpontot. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexnél. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Visszaadja a sorozat adatpontot az index alapján (a gyűjteményben lévő sorozatszáma).

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

Visszaadja a sorozat adatpont indexét (a gyűjteményben lévő sorozatszámát).

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

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok XValue tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.XValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok XValue tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.XValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok YValue tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.YValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok YValue tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.YValue.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok BubbleSize tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.BubbleSize.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok BubbleSize tulajdonság objektumában. Más szóval megadja a ChartDataPointEx.BubbleSize.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok Value tulajdonság objektumában. Más szóval megadja a ChartDataPoint.Value.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Visszatérési érték:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Megadja, hogy az AsCell, AsLiteralString vagy AsLiteralDouble tulajdonság van-e érvényben az adatpontok Value tulajdonság objektumában. Más szóval megadja a ChartDataPoint.Value.Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Megadja az értékek típusát a ChartDataPoint.ErrorBarsCustomValues tulajdonságlistában. Csak olvasás [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Visszatérési érték:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Ha a gyűjtemény már tartalmaz adatpontot az index index-szel, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot az index index==N esetén (amikor a gyűjteményben lévő adatpontok száma kisebb vagy egyenlő N-nél), akkor hozzáadja a hiányzó adatpontokat, és visszaadja az utolsót (amely a kért indexet tartalmazza). Például, a gyűjtemény indexei {0, 1, 2}, a kért index pedig 5. Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5-ös indexű adatpontot.

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Stock alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeStock(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Stock alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeStock(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Line alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeLine(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Line alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeLine(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Scatter alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Radar alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeRadar(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Radar alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeRadar(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Column vagy Bar alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeColumn(ChartType) és a ChartTypeCharacterizer.IsChartTypeBar(ChartType) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Column vagy Bar alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeColumn(ChartType) és a ChartTypeCharacterizer.IsChartTypeBar(ChartType) metódusokat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke az Area alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeArea(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke az Area alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeArea(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Pie alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypePie(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Pie alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypePie(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Doughnut alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Doughnut alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | double | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xValue | java.lang.String | Adatpont XValue |
| yValue | double | Adatpont YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont BubbleSize |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Bubble alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Surface alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chartType értéke a Surface alaptípusok egyike (lásd a ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metódust).

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Sunburst.

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Waterfall.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke BoxAndWhisker.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont Value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IHistogram 
Oops... It seems there was a mistake. The provided line appears truncated. Please provide the full line for accurate translation.
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Treemap.

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

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Histogram.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Funnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Adatpont value |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Új adatpont.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Létrehozza az új adatpontot és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, amelyek chart type értéke Map.

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

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index of a data point to remove. |