---
title: IChartDataPointCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci datových bodů řady.
type: docs
url: /cs/com.aspose.slides/ichartdatapointcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Reprezentuje kolekci datových bodů řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací datový bod řady podle indexu (jeho sériové číslo v této kolekci). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Vrací index (sériové číslo v této kolekci) datového bodu v této kolekci. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Udává, zda je v objektu vlastnosti XValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Udává, zda je v objektu vlastnosti XValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Udává, zda je v objektu vlastnosti YValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Udává, zda je v objektu vlastnosti YValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Udává, zda je v objektu vlastnosti BubbleSize datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Udává, zda je v objektu vlastnosti BubbleSize datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Udává, zda je v objektu vlastnosti Value datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Udává, zda je v objektu vlastnosti Value datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Udává typ hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Pokud kolekce již obsahuje datový bod s indexem index, vrátí tento datový bod. |
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
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Vytvoří nový datový bod a přidá jej na konec kolekce. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Vrací datový bod řady podle indexu (jeho sériové číslo v této kolekci).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Vrací index (sériové číslo v této kolekci) datového bodu v této kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Návratová hodnota:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Udává, zda je v objektu vlastnosti XValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.XValue.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Návratová hodnota:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Udává, zda je v objektu vlastnosti XValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.XValue.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Udává, zda je v objektu vlastnosti YValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.YValue.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Návratová hodnota:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Udává, zda je v objektu vlastnosti YValue datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.YValue.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Udává, zda je v objektu vlastnosti BubbleSize datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.BubbleSize.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Návratová hodnota:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Udává, zda je v objektu vlastnosti BubbleSize datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPointEx.BubbleSize.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Udává, zda je v objektu vlastnosti Value datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Návratová hodnota:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Udává, zda je v objektu vlastnosti Value datových bodů aktivní vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble. Jinými slovy specifikuje typ hodnoty vlastnosti ChartDataPoint.Value.Data. Číst/Zapisovat [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Udává typ hodnot v seznamu vlastností ChartDataPoint.ErrorBarsCustomValues. Pouze pro čtení [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Návratová hodnota:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Pokud kolekce již obsahuje datový bod s indexem index, vrátí tento datový bod. Pokud kolekce neobsahuje datový bod s indexem index==N (když je počet datových bodů v této kolekci menší nebo roven N), přidá chybějící datové body a vrátí poslední (který má požadovaný index). Například kolekce má indexy {0, 1, 2} a požadovaný index je 5. Metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5} a vrátí datový bod s indexem 5.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | long | Index. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Vrací datový bod s požadovaným indexem.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Stock podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Stock podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Line podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Line podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | double | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | double | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Scatter podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | double | Hodnota YValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Radar podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Radar podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze sloupcových nebo pruhových podtypů (viz také metody ChartTypeCharacterizer.IsChartTypeColumn(ChartType) a ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze sloupcových nebo pruhových podtypů (viz také metody ChartTypeCharacterizer.IsChartTypeColumn(ChartType) a ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Area podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Area podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Pie podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Pie podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Doughnut podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Doughnut podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | double | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z Bubble podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xValue | java.lang.String | Hodnota XValue |
| yValue | double | Hodnota YValue |
| bubbleSize | double | Hodnota BubbleSize |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Surface podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden ze Surface podtypů (viz také metoda ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Sunburst.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota SizeValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Treemap.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota SizeValue |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Histogram.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Funnel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hodnota ColorValue datového bodu |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Nový datový bod.
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky z kolekce.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Hodnota. |

### removeAt(int index) {#removeAt-int-}
```
public abstract :   

```

Odstraní prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index datového bodu k odstranění. |