---
title: ChartDataPoint
second_title: Aspose.Slides dla Java – odniesienie API
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
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [getExplosion()](#getExplosion--) | Określa odległość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. |
| [setExplosion(int value)](#setExplosion-int-) | Określa odległość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. |
| [getFormat()](#getFormat--) | Reprezentuje właściwości formatowania. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje właściwości formatowania. |
| [getMarker()](#getMarker--) | Określa znacznik danych. |
| [getSetAsTotal()](#getSetAsTotal--) | Ustawia punkt danych jako sumę. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ustawia punkt danych jako sumę. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Usuwa DataPoint z serii wykresu. |
| [getDataPointLevels()](#getDataPointLevels--) | Zwraca kontener poziomów punktów danych. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że punkt danych ma odwrócić kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że punkt danych ma odwrócić kolory, jeśli wartość jest ujemna. |
| [getCachedValue()](#getCachedValue--) | Pobiera buforowaną wartość punktu danych wykresu. |
| [getCachedXValue()](#getCachedXValue--) | Pobiera buforowaną wartość X punktu danych wykresu. |
| [getCachedYValue()](#getCachedYValue--) | Pobiera buforowaną wartość Y punktu danych wykresu. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Pobiera buforowany rozmiar bąbelka punktu danych wykresu. |
| [getActualX()](#getActualX--) | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. |
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

Zwraca wartość rozmiaru punktu danych wykresu. Używane z wykresami Treemap i Sunburst. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Zwraca wartość koloru punktu danych wykresu. Używane z wykresami mapowymi. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

Określa odległość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Zwraca:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Określa odległość, o jaką punkt danych ma zostać przesunięty od środka wykresu kołowego. Odczyt/zapis int.

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

Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall.

**Zwraca:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall.

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

Zwraca kontener poziomów punktów danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych zaczyna się od zera.

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
public final Color getAutomaticDataPointColor()
```

Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined.

**Zwraca:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Określa, że punkt danych ma odwrócić kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Określa, że punkt danych ma odwrócić kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Pobiera buforowaną wartość punktu danych wykresu. Tylko do odczytu [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Wypisz wszystkie buforowane wartości serii wykresu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Pobiera buforowaną wartość X punktu danych wykresu. Tylko do odczytu [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Wypisz wszystkie buforowane wartości X serii wykresu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Pobiera buforowaną wartość Y punktu danych wykresu. Tylko do odczytu [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Wypisz wszystkie buforowane wartości Y serii wykresu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Pobiera buforowany rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Wypisz wszystkie buforowane wartości rozmiaru bąbelka serii wykresu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float