---
title: ChartDataPointCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje kolekcję punktu danych serii.
type: docs
url: /pl/com.aspose.slides/chartdatapointcollection/
---
**Dziedziczenie:**  
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Reprezentuje kolekcję punktów danych serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt danych serii według indeksu (jego numer seryjny w tej kolekcji). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Zwraca indeks (numer seryjny) punktu danych w tej kolekcji. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Określa typy wartości w liście właściwości ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Jeśli kolekcja już zawiera punkt danych o podanym indeksie, zwraca ten punkt danych. |
| [size()](#size--) | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny wątkowo). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca wylicznik, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
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
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Tworzy nowy punkt danych i dodaje go na koniec kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
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
public final int get_Item(IChartDataPoint pt)
```

Zwraca indeks (numer seryjny) punktu danych w tej kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Zwraca:**  
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.XValue.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**  
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości XValue punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.XValue.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.YValue.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**  
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceForYValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości YValue punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.YValue.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.BubbleSize.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**  
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości BubbleSize punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.BubbleSize.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.Value.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Zwraca:**  
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Określa, czy właściwość AsCell lub AsLiteralString lub AsLiteralDouble jest aktualna w obiekcie właściwości Value punktów danych. Inaczej określa typ wartości właściwości ChartDataPoint.Value.Data. **Odczyt/zapis** [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Określa typy wartości w liście właściwości ChartDataPoint.ErrorBarsCustomValues. **Tylko do odczytu** [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Zwraca:**  
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Jeśli kolekcja już zawiera punkt danych o podanym indeksie, zwraca ten punkt danych. Jeśli kolekcja nie zawiera punktu o indeksie `index==N` (gdy liczba punktów w kolekcji jest mniejsza lub równa N), dodaje brakujące punkty i zwraca ostatni (który ma żądany indeks). Przykład: indeksy kolekcji to {0, 1, 2}, a żądany indeks to 5. Metoda doda brakujące punkty: {0, 1, 2, 3, 4, 5} i zwróci punkt o indeksie 5.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | long | Indeks. |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – zwraca punkt danych o żądanym indeksie.

### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. **Tylko do odczytu** int.

**Zwraca:**  
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopiuje do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| arrayIndex | int | Indeks, od którego rozpocząć kopiowanie. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny wątkowo). **Tylko do odczytu** boolean.

**Zwraca:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. **Tylko do odczytu** Object.

**Zwraca:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Zwraca wylicznik, który iteruje po kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – wylicznik umożliwiający iterację po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – java.util.Iterator dla całej kolekcji.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Stock (zobacz także metodę [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych. |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Stock (zobacz także metodę [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych. |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Line (zobacz także metodę [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych. |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Line (zobacz także metodę [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych. |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Scatter (zobacz także metodę [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Radar (zobacz także metodę [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Radar (zobacz także metodę [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Column lub Bar (zobacz także metody [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) i [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Column lub Bar (zobacz także metody [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) i [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Area (zobacz także metodę [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Area (zobacz także metodę [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Pie (zobacz także metodę [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Pie (zobacz także metodę [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Doughnut (zobacz także metodę [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Doughnut (zobacz także metodę [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | double | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Bubble (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xValue | java.lang.String | XValue punktu danych |
| yValue | double | YValue punktu danych |
| bubbleSize | double | BubbleSize punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Surface (zobacz także metodę [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których `chartType` należy do podtypów Surface (zobacz także metodę [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Sunburst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public               ??
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Treemap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Waterfall.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Histogram.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Funnel.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Wartość punktu danych |

**Zwraca:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii o typie wykresu Map.

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
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – nowy punkt danych.

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Usuwa określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Wartość. |

### removeAt(int index) {#removeAt-int-}
```
public           
```

Usuwa element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks punktu danych do usunięcia. |