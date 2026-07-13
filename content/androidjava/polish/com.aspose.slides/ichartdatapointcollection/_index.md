---
title: IChartDataPointCollection
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje kolekcję punktu danych serii.
type: docs
url: /pl/com.aspose.slides/ichartdatapointcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Reprezentuje kolekcję punktu danych serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt danych serii według indeksu (jego numer seryjny w tej kolekcji). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Zwraca indeks (numer seryjny w tej kolekcji) punktu danych w tej kolekcji. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Określa typ wartości w liście właściwości ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Jeśli kolekcja już zawiera punkt danych z indeksem index, to zwraca ten punkt danych. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Zwraca punkt danych serii według indeksu (jego numer seryjny w tej kolekcji).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Zwraca indeks (numer seryjny w tej kolekcji) punktu danych w tej kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Zwraca:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.XValue.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.XValue.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.YValue.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.YValue.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.BubbleSize.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. W innym słowie określa typ wartości właściwości ChartDataPointEx.BubbleSize.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. W innym słowie określa typ wartości właściwości ChartDataPoint.Value.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. W innym słowie określa typ wartości właściwości ChartDataPoint.Value.Data. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Określa typ wartości w liście właściwości ChartDataPoint.ErrorBarsCustomValues. Read-only [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Zwraca:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Jeśli kolekcja już zawiera punkt danych z indeksem index, to zwraca ten punkt danych. Jeśli kolekcja nie zawiera punktu danych o indeksie index==N (gdy liczba punktów danych w tej kolekcji jest mniejsza lub równa N), metoda dodaje brakujące punkty danych i zwraca ostatni (który ma żądany indeks). Przykładowo, indeksy kolekcji to {0, 1, 2}, a żądany indeks to 5. Wtedy metoda dodaje brakujące punkty: {0, 1, 2, 3, 4, 5} i zwraca punkt danych o indeksie 5.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | long | Indeks. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Zwraca punkt danych o żądanym indeksie.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Stock (zobacz również metodę ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Stock (zobacz również metodę ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Line (zobacz również metodę ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Line (zobacz również metodę ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Scatter (zobacz również metodę ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Radar (zobacz również metodę ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Radar (zobacz również metodę ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Column lub Bar (zobacz również metodę ChartTypeCharacterizer.IsChartTypeColumn(ChartType) oraz ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Column lub Bar (zobacz również metodę ChartTypeCharacterizer.IsChartTypeColumn(ChartType) oraz ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Area (zobacz również metodę ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Area (zobacz również metodę ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Pie (zobacz również metodę ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Pie (zobacz również metodę ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Doughnut (zobacz również metodę ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Doughnut (zobacz również metodę ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Bubble (zobacz również metodę ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Surface (zobacz również metodę ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której chartType jest jednym z podtypów Surface (zobacz również metodę ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Sunburst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Waterfall.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Treemap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Histogram.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Funnel.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie dla serii, w której typ wykresu to Map.

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


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue punktu danych |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nowy punkt danych.

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Usuwa określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Wartość. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks punktu danych do usunięcia. |