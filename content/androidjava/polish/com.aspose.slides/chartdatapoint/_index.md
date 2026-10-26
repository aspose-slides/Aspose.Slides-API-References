---
title: ChartDataPoint
second_title: Aspose.Slides dla Androida przez Java API Reference
description: Reprezentuje punkt danych serii.
type: docs
url: /pl/com.aspose.slides/chartdatapoint/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Reprezentuje punkt danych serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Zwraca wartość rozmiaru punktu danych wykresu. |
| [getColorValue()](#getColorValue--) | Zwraca wartość koloru punktu danych wykresu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje wartości pasków błędów serii w przypadku typu wartości Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [getExplosion()](#getExplosion--) | Określa ilość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego. |
| [setExplosion(int value)](#setExplosion-int-) | Określa ilość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego. |
| [getFormat()](#getFormat--) | Reprezentuje właściwości formatowania. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje właściwości formatowania. |
| [getMarker()](#getMarker--) | Określa znacznik danych. |
| [getSetAsTotal()](#getSetAsTotal--) | Ustawia punkt danych jako całkowity. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ustawia punkt danych jako całkowity. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Usuwa DataPoint z serii wykresu. |
| [getDataPointLevels()](#getDataPointLevels--) | Zwraca kontener poziomów punktu danych. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Zwraca automatyczny kolor punktu danych oparty na indeksie serii, indeksie punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. |
| [getActualX()](#getActualX--) | Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualY()](#getActualY--) | Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualWidth()](#getActualWidth--) | Określa rzeczywistą szerokość elementu wykresu. |
| [getActualHeight()](#getActualHeight--) | Określa rzeczywistą wysokość elementu wykresu. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Tylko do odczytu [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Zwraca:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Zwraca wartość rozmiaru punktu danych wykresu. Używane w wykresach Treemap i Sunburst. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Zwraca wartość koloru punktu danych wykresu. Używane w wykresach Map. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje wartości pasków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Zwraca:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Tylko do odczytu [IDataLabel](../../com.aspose.slides/idatalabel).

**Zwraca:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Określa ilość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Zwraca:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Określa ilość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje właściwości formatowania. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje właściwości formatowania. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Określa znacznik danych. Tylko do odczytu [IMarker](../../com.aspose.slides/imarker).

**Zwraca:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla typu serii Waterfall.

**Zwraca:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla typu serii Waterfall.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

Usuwa DataPoint z serii wykresu.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Zwraca kontener poziomów punktu danych. Zastosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktu danych rozpoczyna się od zera.

**Zwraca:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Zwraca:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Zwraca automatyczny kolor punktu danych oparty na indeksie serii, indeksie punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined.

**Zwraca:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Odczyt float.

**Zwraca:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Odczyt float.

**Zwraca:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Odczyt float.

**Zwraca:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Odczyt float.

**Zwraca:**
float