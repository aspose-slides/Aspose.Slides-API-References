---
title: ChartDataPointCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci datových bodů řady.
type: docs
url: /cs/com.aspose.slides/chartdatapointcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Představuje kolekci datového bodu řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací datový bod řady podle indexu (jeho pořadové číslo v této kolekci). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Vrátí index (pořadové číslo) datového bodu v této kolekci. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Určuje, zda je v objektu vlastnosti XValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Určuje, zda je v objektu vlastnosti XValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Určuje, zda je v objektu vlastnosti YValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Určuje, zda je v objektu vlastnosti YValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Určuje, zda je v objektu vlastnosti BubbleSize datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Určuje, zda je v objektu vlastnosti BubbleSize datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Určuje, zda je v objektu vlastnosti Value datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Určuje, zda je v objektu vlastnosti Value datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Určuje typy hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Pokud kolekce již obsahuje datový bod s indexem index, vrátí tento datový bod. |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která naznačuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přaddá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Vrací datový bod řady podle indexu (jeho pořadové číslo v této kolekci).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Vrátí index (pořadové číslo) datového bodu v této kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Vrací:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Určuje, zda je v objektu vlastnosti XValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.XValue.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Určuje, zda je v objektu vlastnosti XValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.XValue.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Určuje, zda je v objektu vlastnosti YValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.YValue.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceForYValues(int value)
```

Určuje, zda je v objektu vlastnosti YValue datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.YValue.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Určuje, zda je v objektu vlastnosti BubbleSize datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.BubbleSize.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Určuje, zda je v objektu vlastnosti BubbleSize datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.BubbleSize.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Určuje, zda je v objektu vlastnosti Value datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Určuje, zda je v objektu vlastnosti Value datových bodů aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy určuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Určuje typy hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. Pouze ke čtení [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Vrací:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Pokud kolekce již obsahuje datový bod s indexem index, vrátí tento datový bod. Pokud kolekce neobsahuje datový bod s indexem index==N (když je počet datových bodů v této kolekci menší nebo roven N), pak přidá chybějící datové body a vrátí poslední (který má požadovaný index). Například indexy kolekce jsou {0, 1, 2} a požadovaný index je 5. Pak metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5}. A vrátí datový bod s indexem 5.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | long | Index. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Vrací datový bod s požadovaným indexem.

### size() {#size--}
```
public final int size()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze ke čtení int.

**Vrací:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Zkopíruje do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole, do kterého se kopíruje. |
| arrayIndex | int | Index, od kterého se začíná kopírovat. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která naznačuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator pro celou kolekci.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Stock (viz také metoda [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Stock (viz také metoda [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Line (viz také metoda [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Line (viz také metoda [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota X datového bodu |
| yValue | double | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota X datového bodu |
| yValue | double | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Scatter (viz také metoda [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota X datového bodu |
| yValue | double | Hodnota Y datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Radar (viz také metoda [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Radar (viz také metoda [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Column nebo Bar (viz také metody [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) a [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Column nebo Bar (viz také metody [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) a [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Area (viz také metoda [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Area (viz také metoda [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Pie (viz také metoda [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Pie (viz také metoda [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Doughnut (viz také metoda [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Doughnut (viz také metoda [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bubliny |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bubliny |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota X datového bodu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota Y datového bodu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bubliny |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota X datového bodu |
| yValue | double | Hodnota Y datového bodu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bubliny |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota X datového bodu |
| yValue | double | Hodnota Y datového bodu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bubliny |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také metoda [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Datový bod XValue |
| yValue | double | Datový bod YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Datový bod XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Datový bod XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod XValue |
| yValue | double | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Datový bod XValue |
| yValue | double | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Bubble (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Datový bod XValue |
| yValue | double | Datový bod YValue |
| bubbleSize | double | Datový bod BubbleSize |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Surface (viz také [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Surface (viz také [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Sunburst.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod SizeValue |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Treemap.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod SizeValue |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Histogram.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Funnel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod Value |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Map.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Datový bod ColorValue |

**Návratová hodnota:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový datový bod.

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Hodnota. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index datového bodu, který se má odstranit. |