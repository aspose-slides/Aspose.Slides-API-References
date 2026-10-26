---
title: ChartDataPointCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci bodu dat řady.
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

Representuje kolekci bodů dat řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací bod dat řady podle indexu (jeho pořadové číslo v této kolekci). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Vrací index (pořadové číslo) bodu dat v této kolekci. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Určuje, zda je ve vlastnosti XValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Určuje, zda je ve vlastnosti XValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Určuje, zda je ve vlastnosti YValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Určuje, zda je ve vlastnosti YValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Určuje, zda je ve vlastnosti BubbleSize objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Určuje, zda je ve vlastnosti BubbleSize objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Určuje, zda je ve vlastnosti Value objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Určuje, zda je ve vlastnosti Value objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Určuje typy hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Pokud kolekce již obsahuje bod dat s indexem index, vrátí tento bod. |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový bod dat a přidá jej na konec kolekce. |
| [clear()](#clear--) | Odstraňuje všechny prvky ze sbírky. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Odstraňuje zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje prvek na zadaném indexu. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Vrací bod dat řady podle indexu (jeho pořadové číslo v této kolekci).

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

Vrací index (pořadové číslo) bodu dat v této kolekci.

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

Určuje, zda je ve vlastnosti XValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.XValue.Data. Pouze pro čtení [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Určuje, zda je ve vlastnosti XValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.XValue.Data. Číst/zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Určuje, zda je ve vlastnosti YValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.YValue.Data. Pouze pro čtení [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Určuje, zda je ve vlastnosti YValue objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.YValue.Data. Číst/zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Určuje, zda je ve vlastnosti BubbleSize objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.BubbleSize.Data. Pouze pro čtení [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Určuje, zda je ve vlastnosti BubbleSize objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.BubbleSize.Data. Číst/zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Určuje, zda je ve vlastnosti Value objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Pouze pro čtení [DataSourceType](../../com.aspose.slides/datasourcetype).

**Vrací:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Určuje, zda je ve vlastnosti Value objektu bodu dat aktuální vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinak řečeno určuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Číst/zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Určuje typy hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. Pouze pro čtení [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Vrací:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Pokud kolekce již obsahuje bod dat s indexem index, vrátí tento bod. Pokud kolekce neobsahuje bod dat s indexem index==N (když je počet bodů v této kolekci menší nebo roven N), přidá chybějící body a vrátí poslední (který má požadovaný index). Například kolekce má indexy \{0, 1, 2\} a požadovaný index je 5. Pak metoda přidá chybějící body: \{0, 1, 2, 3, 4, 5\} a vrátí bod s indexem 5.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | long | Index. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Vrací bod dat s požadovaným indexem.
### size() {#size--}
```
public final int size()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Zkopíruje do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole, do kterého se kopíruje. |
| arrayIndex | int | Index, od kterého se začne kopírovat. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

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

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Stock podtypů (viz také [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Stock podtypů (viz také [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Line podtypů (viz také [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Line podtypů (viz také [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | double | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | double | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | double | YValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Radar podtypů (viz také [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Radar podtypů (viz také [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metoda).

**Parametry::
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Column nebo Bar podtypů (viz také [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) a [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Column nebo Bar podtypů (viz také [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) a [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Area podtypů (viz také [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Area podtypů (viz také [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Pie podtypů (viz také [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Pie podtypů (viz také [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Doughnut podtypů (viz také [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Doughnut podtypů (viz také [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Bubble podtypů (viz také [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | XValue bodu dat |
| yValue | double | YValue bodu dat |
| bubbleSize | double | BubbleSize bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Surface podtypů (viz také [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Surface podtypů (viz také [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) metoda).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Sunburst.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Treemap.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota velikosti bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Histogram.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Funnel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Vytvoří nový bod dat a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota ColorValue bodu dat |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nový bod dat.
### clear() {#clear--}
```
public final void clear()
```

Odstraňuje všechny prvky ze sbírky.
### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Odstraňuje zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Hodnota. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraňuje prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index bodu dat, který se má odstranit. |
