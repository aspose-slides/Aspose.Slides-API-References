---
title: IChartDataPoint
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Reprezentuje punkt danych serii.
type: docs
url: /pl/com.aspose.slides/ichartdatapoint/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Reprezentuje punkt danych serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXValue()](#getXValue--) | Zwraca wartość x punktu danych wykresu. |
| [getYValue()](#getYValue--) | Zwraca wartość y punktu danych wykresu. |
| [getBubbleSize()](#getBubbleSize--) | Zwraca rozmiar bąbelka punktu danych wykresu. |
| [getValue()](#getValue--) | Zwraca wartość punktu danych wykresu. |
| [getSizeValue()](#getSizeValue--) | Zwraca wartość rozmiaru punktu danych wykresu. |
| [getColorValue()](#getColorValue--) | Zwraca wartość koloru punktu danych wykresu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. |
| [getLabel()](#getLabel--) | Reprezentuje etykietę punktu danych wykresu. |
| [isBubble3D()](#isBubble3D--) | Określa, że bąbelki mają zastosowany efekt 3-D. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Określa, że bąbelki mają zastosowany efekt 3-D. |
| [getExplosion()](#getExplosion--) | Określa ilość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. |
| [setExplosion(int value)](#setExplosion-int-) | Określa ilość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. |
| [getFormat()](#getFormat--) | Reprezentuje właściwości formatowania. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje właściwości formatowania. |
| [getMarker()](#getMarker--) | Określa znacznik danych. |
| [remove()](#remove--) | Usuwa DataPoint z serii wykresu. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ustawia punkt danych jako całkowity. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ustawia punkt danych jako całkowity. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. |
| [getDataPointLevels()](#getDataPointLevels--) | Zwraca kontener poziomów punktów danych. |
| [getIndex()](#getIndex--) | Określa, do której kolekcji elementów potomnych rodzica ten punkt danych się odnosi. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Zwraca wartość x punktu danych wykresu. Tylko do odczytu [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Zwraca:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Zwraca wartość y punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Zwraca rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Zwraca wartość punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Zwraca wartość rozmiaru punktu danych wykresu. Używane w wykresach Treemap i Sunburst. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Zwraca wartość koloru punktu danych wykresu. Używane w wykresach map. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Zwraca:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Reprezentuje etykietę punktu danych wykresu. Tylko do odczytu [IDataLabel](../../com.aspose.slides/idatalabel).

**Zwraca:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Określa, że bąbelki mają zastosowany efekt 3-D. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Określa, że bąbelki mają zastosowany efekt 3-D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Określa ilość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Zwraca:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Określa ilość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje właściwości formatowania. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Reprezentuje właściwości formatowania. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Określa znacznik danych. Tylko do odczytu [IMarker](../../com.aspose.slides/imarker).

**Zwraca:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Usuwa DataPoint z serii wykresu.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType ma wartość NotDefined.

**Zwraca:**
java.lang.Integer - Automatyczny kolor punktu danych java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla typu serii Waterfall.

**Zwraca:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla typu serii Waterfall.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Zwraca kontener poziomów punktów danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych zaczyna się od zera.

**Zwraca:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Określa, do której kolekcji elementów potomnych rodzica ten punkt danych się odnosi. Tylko do odczytu long.

**Zwraca:**
long