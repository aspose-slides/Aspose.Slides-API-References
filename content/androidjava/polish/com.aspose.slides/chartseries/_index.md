---
title: ChartSeries
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje serię wykresu.
type: docs
url: /pl/com.aspose.slides/chartseries/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Reprezentuje serię wykresu.

## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getExplosion()](#getExplosion--) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [setExplosion(int value)](#setExplosion-int-) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [getSmooth()](#getSmooth--) | Represents curve smoothing. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Represents curve smoothing. |
| [getName()](#getName--) | Return series name. |
| [getDataPoints()](#getDataPoints--) | Returns collection of data points of this series. |
| [getType()](#getType--) | Returns a type of this series. |
| [setType(int value)](#setType-int-) | Returns a type of this series. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if this series is plotted on secondary axis. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indicates if this series is plotted on secondary axis. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Returns the format of a series. |
| [getOrder()](#getOrder--) | Returns the order of a series. |
| [setOrder(int value)](#setOrder-int-) | Returns the order of a series. |
| [getLabels()](#getLabels--) | Returns the Labels of a series. |
| [getTrendLines()](#getTrendLines--) | Collection of series trend lines. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Represents ErrorBars of series with derection X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Represents ErrorBars of series with derection Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specifies the shape of a series of a 3-D bar chart. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specifies the shape of a series of a 3-D bar chart. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specifies invert solid color for series. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returns an automatic color of series based on series index and chart style. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Represents inner points. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Represents inner points. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Represents outlier points. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Represents outlier points. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Represents mean markers. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Represents mean markers. |
| [getShowMeanLine()](#getShowMeanLine--) | Represents mean line. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Represents mean line. |
| [getQuartileMethod()](#getQuartileMethod--) | Represents quartile method. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Represents quartile method. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Represents connector lines. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Represents connector lines. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Represents layout of parent category labels. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Represents layout of parent category labels. |
| [hasUpDownBars()](#hasUpDownBars--) | Determines whether Line- or Stock-chart has a up/down bars. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [hasSeriesLines()](#hasSeriesLines--) | Determines whether there are series lines for this series and kindred series. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**  
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Odległość otwartego wycinka koła od środka wykresu kołowego wyrażona jest jako procent średnicy koła. Odczyt/zapis int.

**Zwraca:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Odległość otwartego wycinka koła od środka wykresu kołowego wyrażona jest jako procent średnicy koła. Odczyt/zapis int.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Reprezentuje wygładzanie krzywej. True, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub punktowego. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Reprezentuje wygładzanie krzywej. True, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub punktowego. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Zwraca nazwę serii. Tylko do odczytu [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Zwraca:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Zwraca kolekcję punktów danych tej serii. Tylko do odczytu [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Zwraca:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Zwraca typ tej serii. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Zwraca:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Zwraca typ tej serii. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Wskazuje, czy ta seria jest rysowana na osi wtórnej. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Wskazuje, czy ta seria jest rysowana na osi wtórnej. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Tylko do odczytu [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Zwraca:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Zwraca format serii. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Zwraca kolejność serii. Odczyt/zapis int.

**Zwraca:**  
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Zwraca kolejność serii. Odczyt/zapis int.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Zwraca etykiety serii. Tylko do odczytu [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Zwraca:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Kolekcja linii trendu serii. Tylko do odczytu [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Linie trendu są dostępne (nie null) dla serii danych w wykresach 2-D nieukładanych: area, bar, column, line, stock, xy (scatter) i bubble. Linia trendu nie jest dostępna dla serii w wykresach układanych ani 3-D. Linia trendu nie jest również dostępna dla wykresów radar, pie, surface ani doughnut.

**Zwraca:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Reprezentuje ErrorBars serii z kierunkiem X. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars z kierunkiem X są dostępne dla serii typów area, bar, scatter i bubble. Dla innych typów wykresu właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z własnością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje ErrorBars serii z kierunkiem Y. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars z kierunkiem Y są dostępne dla serii typów area, bar, line, scatter i bubble. Dla innych typów wykresu właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z własnością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje wpis legendy powiązany z tą serią. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Odczyt/zapis String.

**Zwraca:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Odczyt/zapis String.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Odczyt/zapis String.

**Zwraca:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Odczyt/zapis String.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Odczyt/zapis String.

**Zwraca:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Odczyt/zapis String.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Odczyt/zapis String.

**Zwraca:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Odczyt/zapis String.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Tylko do odczytu [IMarker](../../com.aspose.slides/imarker).

**Zwraca:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Określa kształt serii wykresu słupkowego 3-D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Zwraca:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Określa kształt serii wykresu słupkowego 3-D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Określa odwrócony jednolity kolor dla serii. Aby zastosować ustawienie koloru, ustaw format serii FillType na FillType.Solid. Odczyt/zapis [ColorFormat](../../com.aspose.slides/colorformat).

**Zwraca:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType jest równy NotDefined.

**Zwraca:**  
java.lang.Integer - obiekt java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Reprezentuje wewnętrzne punkty. True, jeśli wewnętrzne punkty są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Reprezentuje wewnętrzne punkty. True, jeśli wewnętrzne punkty są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Reprezentuje punkty odstające. True, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Reprezentuje punkty odstające. True, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Reprezentuje znaczniki średniej. True, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Reprezentuje znaczniki średniej. True, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Reprezentuje linię średniej. True, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Reprezentuje linię średniej. True, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Reprezentuje metodę kwartylu. Dotyczy wyłącznie wykresów BoxAndWhisker.

**Zwraca:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Reprezentuje metodę kwartylu. Dotyczy wyłącznie wykresów BoxAndWhisker.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall.

**Zwraca:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Reprezentuje układ etykiet kategorii nadrzędnych. Dotyczy wyłącznie wykresów Treemap.

**Zwraca:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Reprezentuje układ etykiet kategorii nadrzędnych. Dotyczy wyłącznie wykresów Treemap.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Określa, czy wykres liniowy lub giełdowy posiada słupki góra/dół. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars, aby sformatować słupki góra/dół. Tylko do odczytu boolean.

--------------------

To jest projekcja własności ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Zwraca:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.GapWidth, aby zmienić wartość. Tylko do odczytu int.

--------------------

To jest projekcja własności ParentSeriesGroup.GapWidth.

**Zwraca:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Zwraca lub ustawia odległość, jako procent szerokości znacznika, między seriami danych w wykresie 3D. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.GapDepth, aby zmienić wartość. Tylko do odczytu int.

--------------------

To jest projekcja własności ParentSeriesGroup.GapDepth.

**Zwraca:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Określa kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.FirstSliceAngle, aby zmienić wartość. Tylko do odczytu int.

--------------------

To jest projekcja własności ParentSeriesGroup.FirstSliceAngle.

**Zwraca:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize, aby zmienić wartość. Tylko do odczytu byte.

--------------------

To jest projekcja własności ParentSeriesGroup.DoughnutHoleSize.

**Zwraca:**  
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Określa, jak bardzo słupki i kolumny zachodzą na siebie w wykresach 2-D, jako procent (od -100 % do 100 %). To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej. Jest to projekcja odpowiedniej własności w grupie nadrzędnej, więc własność jest tylko do odczytu. Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap (odczyt/zapis). Tylko do odczytu byte.

--------------------

Overlap określa stopień zachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:  
- -100 %: maksymalny odstęp (słupki całkowicie oddzielone).  
0 %: słupki umieszczone obok siebie bez zachodzenia ani odstępu.  
100 %: maksymalne zachodzenie (słupki całkowicie na siebie nachodzą). To jest projekcja własności ParentSeriesGroup.Overlap.

**Zwraca:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Określa rozmiar drugiego wycinka lub słupka wykresu pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.SecondPieSize, aby zmienić wartość. Tylko do odczytu int.

--------------------

To jest projekcja własności ParentSeriesGroup.SecondPieSize.

**Zwraca:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Określa, czy istnieją linie serii dla tej serii i powiązanych serii. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.HasSeriesLines, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat, aby sformatować linie serii. Tylko do odczytu boolean.

--------------------

To jest projekcja własności ParentSeriesGroup.HasSeriesLines.

**Zwraca:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Określa, w jaki sposób wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.BubbleSizeRepresentation, aby zmienić wartość.

--------------------

To jest projekcja własności ParentSeriesGroup.BubbleSizeRepresentation.

**Zwraca:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Określa wartość używaną do określenia, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.PieSplitPosition, aby zmienić wartość. Tylko do odczytu double.

--------------------

To jest projekcja własności ParentSeriesGroup.PieSplitPosition.

**Zwraca:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Określa, jak określić, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie pie-of-pie lub bar-of-pie. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.PieSplitBy, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) To jest projekcja własności ParentSeriesGroup.PieSplitBy.  
2) Jeśli wartość własności jest PieSplitType.Custom, można zdefiniować własne informacje o podziale za pomocą właściwości ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Własne informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z podziałem niestandardowym. Zawiera punkty danych, które powinny być rysowane w drugim wycinku lub słupku w wykresie pie-of-pie lub bar-of-pie. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Tylko do odczytu [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

To jest projekcja własności ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.IsColorVaried, aby zmienić wartość. Tylko do odczytu boolean.

--------------------

To jest projekcja własności ParentSeriesGroup.IsColorVaried.

**Zwraca:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). To nie jest własność tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.BubbleSizeScale, aby zmienić wartość.

--------------------

To jest projekcja własności ParentSeriesGroup.BubbleSizeScale.

**Zwraca:**  
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**  
[IPresentation](../../com.aspose.slides/ipresentation)