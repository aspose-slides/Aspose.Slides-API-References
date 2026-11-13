---
title: IChartDataPoint
second_title: Aspose.Slides dla Java - dokumentacja API
description: Reprezentuje punkt danych serii.
type: docs
url: /pl/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Reprezentuje punkt danych serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXValue()](#getXValue--) | Pobiera wartość x punktu danych wykresu. |
| [getYValue()](#getYValue--) | Pobiera wartość y punktu danych wykresu. |
| [getBubbleSize()](#getBubbleSize--) | Pobiera rozmiar bąbelka punktu danych wykresu. |
| [getValue()](#getValue--) | Pobiera wartość punktu danych wykresu. |
| [getCachedXValue()](#getCachedXValue--) | Pobiera buforowaną wartość X punktu danych wykresu. |
| [getCachedYValue()](#getCachedYValue--) | Pobiera buforowaną wartość Y punktu danych wykresu. |
| [getCachedValue()](#getCachedValue--) | Pobiera buforowaną wartość punktu danych wykresu. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Pobiera buforowany rozmiar bąbelka punktu danych wykresu. |
| [getSizeValue()](#getSizeValue--) | Pobiera wartość rozmiaru punktu danych wykresu. |
| [getColorValue()](#getColorValue--) | Pobiera wartość koloru punktu danych wykresu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. |
| [getLabel()](#getLabel--) | Reprezentuje etykietę punktu danych wykresu. |
| [isBubble3D()](#isBubble3D--) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Określa, że bąbelki mają zastosowany efekt 3D. |
| [getExplosion()](#getExplosion--) | Określa, o ile punkt danych ma być przesunięty od środka wykresu kołowego. |
| [setExplosion(int value)](#setExplosion-int-) | Określa, o ile punkt danych ma być przesunięty od środka wykresu kołowego. |
| [getFormat()](#getFormat--) | Reprezentuje właściwości formatowania. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje właściwości formatowania. |
| [getMarker()](#getMarker--) | Określa znacznik danych. |
| [remove()](#remove--) | Usuwa DataPoint z serii wykresu. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType jest równy NotDefined. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Właściwości odpowiadającego wpisu legendy w przypadku typów wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ustawia punkt danych jako sumę. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ustawia punkt danych jako sumę. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. |
| [getDataPointLevels()](#getDataPointLevels--) | Zwraca kontener poziomów punktu danych. |
| [getIndex()](#getIndex--) | Określa, do której kolekcji potomków rodzica odnosi się ten punkt danych. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Pobiera wartość x punktu danych wykresu. Tylko do odczytu [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Zwraca:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Pobiera wartość y punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Pobiera rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Pobiera wartość punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
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
public abstract ICachedChartValue getCachedYValue()
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
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
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
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
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
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Pobiera wartość rozmiaru punktu danych wykresu. Używane w wykresach Treemap i Sunburst. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Pobiera wartość koloru punktu danych wykresu. Używane w wykresach map. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

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


Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Określa, o ile punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Zwraca:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Określa, o ile punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis int.

**Parametry:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
public abstract Color getAutomaticDataPointColor()
```


Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType jest równy NotDefined.

**Zwraca:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Właściwości odpowiadającego wpisu legendy w przypadku typów wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall.

**Zwraca:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall.

**Parametry:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Zwraca kontener poziomów punktu danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktu danych zaczyna się od zera.

**Zwraca:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Określa, do której kolekcji potomków rodzica odnosi się ten punkt danych. Odczyt long.

**Zwraca:**
long