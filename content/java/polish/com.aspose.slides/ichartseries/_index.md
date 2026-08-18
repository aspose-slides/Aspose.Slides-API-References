---
title: IChartSeries
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje serię wykresu.
type: docs
url: /pl/com.aspose.slides/ichartseries/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Reprezentuje serię wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getExplosion()](#getExplosion--) | Odległość otwartego kawałka koła od środka wykresu kołowego wyrażona jest jako procent średnicy wykresu kołowego. |
| [setExplosion(int value)](#setExplosion-int-) | Odległość otwartego kawałka koła od środka wykresu kołowego wyrażona jest jako procent średnicy wykresu kołowego. |
| [getSmooth()](#getSmooth--) | Reprezentuje wygładzanie krzywej. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Reprezentuje wygładzanie krzywej. |
| [getMarker()](#getMarker--) | Zwraca znacznik serii. |
| [getBar3DShape()](#getBar3DShape--) | Określa kształt serii wykresu słupkowego 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Określa kształt serii wykresu słupkowego 3D. |
| [getName()](#getName--) | Zwraca nazwę serii. |
| [getDataPoints()](#getDataPoints--) | Zwraca kolekcję punktów danych tej serii. |
| [getType()](#getType--) | Zwraca typ tej serii. |
| [setType(int value)](#setType-int-) | Zwraca typ tej serii. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Zwraca grupę nadrzędną serii. |
| [getFormat()](#getFormat--) | Zwraca format serii. |
| [getOrder()](#getOrder--) | Zwraca kolejność serii. |
| [setOrder(int value)](#setOrder-int-) | Zwraca kolejność serii. |
| [getLabels()](#getLabels--) | Zwraca etykiety serii. |
| [getTrendLines()](#getTrendLines--) | Kolekcja linii trendu serii Tylko do odczytu [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Reprezentuje ErrorBars serii z kierunkiem X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Reprezentuje ErrorBars serii z kierunkiem Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy ta seria jest wykreślana na drugiej osi wartości. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Wskazuje, czy ta seria jest wykreślana na drugiej osi wartości. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Zwraca lub ustawia format liczbowy wartości serii. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Zwraca lub ustawia format liczbowy wartości serii. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Zwraca lub ustawia format liczbowy wartości x serii. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Zwraca lub ustawia format liczbowy wartości x serii. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Zwraca lub ustawia format liczbowy wartości y serii. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Zwraca lub ustawia format liczbowy wartości y serii. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Zwraca lub ustawia format liczbowy rozmiarów bąbelków serii. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Zwraca lub ustawia format liczbowy rozmiarów bąbelków serii. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że seria słupkowa, kolumnowa lub bąbelkowa odwróci swoje kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że seria słupkowa, kolumnowa lub bąbelkowa odwróci swoje kolory, jeśli wartość jest ujemna. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Określa odwrócenie jednolitego koloru dla serii. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje element legendy powiązany z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Reprezentuje wewnętrzne punkty. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Reprezentuje wewnętrzne punkty. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Reprezentuje punkty odstające. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Reprezentuje punkty odstające. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Reprezentuje znaczniki średniej. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Reprezentuje znaczniki średniej. |
| [getShowMeanLine()](#getShowMeanLine--) | Reprezentuje znaczniki średniej. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Reprezentuje znaczniki średniej. |
| [getQuartileMethod()](#getQuartileMethod--) | Reprezentuje metodę kwartylu. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Reprezentuje metodę kwartylu. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Reprezentuje linie łączące. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Reprezentuje linie łączące. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Reprezentuje układ etykiet rodzicielskiej kategorii. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Reprezentuje układ etykiet rodzicielskiej kategorii. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300% domyślnego rozmiaru). |
| [hasUpDownBars()](#hasUpDownBars--) | Określa, czy wykres liniowy lub giełdowy posiada słupki góra/dół. |
| [getGapWidth()](#getGapWidth--) | Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [hasSeriesLines()](#hasSeriesLines--) | Określa, czy istnieją linie serii dla tej serii i pokrewnych serii. |
| [getOverlap()](#getOverlap--) | Określa, jak bardzo słupki i kolumny zachodzą na siebie w wykresach 2D, wyrażone jako procent (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego koła lub słupka wykresu pie-of-pie albo bar-of-pie, wyrażony jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku wykresu pie-of-pie lub bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku wykresu pie-of-pie lub bar-of-pie. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10% do 90% rozmiaru obszaru wykresu). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Określa kąt pierwszego kawałka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informacje o niestandardowym podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa sposób reprezentacji wartości rozmiaru bąbelków na wykresie bąbelkowym. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Odległość otwartego kawałka koła od środka wykresu kołowego wyrażona jest jako procent średnicy wykresu kołowego. Odczyt/zapis int.

**Zwraca:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Odległość otwartego kawałka koła od środka wykresu kołowego wyrażona jest jako procent średnicy wykresu kołowego. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Reprezentuje wygładzanie krzywej. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Reprezentuje wygładzanie krzywej. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Zwraca znacznik serii. Tylko do odczytu [IMarker](../../com.aspose.slides/imarker).

**Zwraca:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Określa kształt serii wykresu słupkowego 3D. Changing of value of this property can cause to automatically changing Type of series. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Zwraca:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Określa kształt serii wykresu słupkowego 3D. Changing of value of this property can cause to automatically changing Type of series. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Zwraca nazwę serii. Tylko do odczytu [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Zwraca:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Zwraca kolekcję punktów danych tej serii. Tylko do odczytu [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Zwraca:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Zwraca typ tej serii. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Zwraca typ tej serii. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Zwraca grupę nadrzędną serii. Tylko do odczytu [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Zwraca:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Zwraca format serii. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Zwraca kolejność serii. Odczyt/zapis int.

**Zwraca:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Zwraca kolejność serii. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Zwraca etykiety serii. Tylko do odczytu [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Zwraca:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Kolekcja linii trendu serii Tylko do odczytu [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Zwraca:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Reprezentuje ErrorBars serii z kierunkiem X. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars z kierunkiem X są dostępne dla serii typu area, bar, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje ErrorBars serii z kierunkiem Y. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars z kierunkiem Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Wskazuje, czy ta seria jest wykreślana na drugiej osi wartości. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Wskazuje, czy ta seria jest wykreślana na drugiej osi wartości. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Zwraca lub ustawia format liczbowy wartości serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Zwraca lub ustawia format liczbowy wartości serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Zwraca lub ustawia format liczbowy wartości x serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Zwraca lub ustawia format liczbowy wartości x serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Zwraca lub ustawia format liczbowy wartości y serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Zwraca lub ustawia format liczbowy wartości y serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Zwraca lub ustawia format liczbowy rozmiarów bąbelków serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Zwraca lub ustawia format liczbowy rozmiarów bąbelków serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Określa, że seria słupkowa, kolumnowa lub bąbelkowa odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Określa, że seria słupkowa, kolumnowa lub bąbelkowa odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Określa odwrócenie jednolitego koloru dla serii. To apply color setting set series format FillType to FillType.Solid. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje element legendy powiązany z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Zwraca automatyczny kolor serii oparty na indeksie serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType jest równe NotDefined.

**Zwraca:**
java.awt.Color - Automatyczny kolor serii java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Reprezentuje znaczniki średniej. Prawda, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Reprezentuje znaczniki średniej. Prawda, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Reprezentuje metodę kwartyli. Dotyczy wyłącznie wykresów BoxAndWhisker.

**Zwraca:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Reprezentuje metodę kwartyli. Dotyczy wyłącznie wykresów BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall.

**Zwraca:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Reprezentuje układ etykiet kategorii nadrzędnych. Dotyczy wyłącznie wykresów Treemap.

**Zwraca:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Reprezentuje układ etykiet kategorii nadrzędnych. Dotyczy wyłącznie wykresów Treemap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 % domyślnego rozmiaru). To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeScale odczyt/zapis, aby zmienić wartość.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.BubbleSizeScale.

**Zwraca:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Określa, czy wykres liniowy lub giełdowy posiada paski górne/dolne. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars do formatowania pasków górnych/dolnych. Tylko do odczytu boolean.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Zwraca:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.GapWidth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.GapWidth.

**Zwraca:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Zwraca lub ustawia odległość, wyrażoną jako procent szerokości markera, pomiędzy seriami danych w wykresie 3D. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.GapDepth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.GapDepth.

**Zwraca:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.IsColorVaried odczyt/zapis, aby zmienić wartość. Tylko do odczytu boolean.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.IsColorVaried.

**Zwraca:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Określa, czy istnieją linie serii dla tej serii i powiązanych serii. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.HasSeriesLines odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat do formatowania linii serii. Tylko do odczytu boolean.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.HasSeriesLines.

**Zwraca:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Określa, jak bardzo słupki i kolumny nachodzą na siebie w wykresach 2-D, wyrażone jako procent (od –100 % do 100 %). To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej. Jest to projekcja odpowiedniej właściwości w grupie serii nadrzędnej, dlatego własność jest tylko do odczytu. Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap odczyt/zapis. Tylko do odczytu byte.

--------------------

Nachodzenie określa stopień nakładania się lub odstępu pomiędzy słupkami i kolumnami jako procent ich szerokości:
- –100 %: maksymalny odstęp (słupki są całkowicie odseparowane).
- 0 %: słupki są ułożone obok siebie bez nakładania się ani odstępu.
- 100 %: maksymalne nakładanie się (słupki całkowicie na siebie nachodzą). To jest projekcja właściwości ParentSeriesGroup.Overlap.

**Zwraca:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Określa rozmiar drugiego wycinka lub słupka wykresu pie-of-pie lub bar-of-pie, wyrażony jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 %). To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.SecondPieSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.SecondPieSize.

**Zwraca:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Określa wartość używaną do określenia, które punkty danych znajdują się w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. Jest używana razem z właściwością PieSplitBy. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitPosition odczyt/zapis, aby zmienić wartość. Tylko do odczytu double.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.PieSplitPosition.

**Zwraca:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Określa sposób określania, które punkty danych znajdują się w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitBy odczyt/zapis, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jest to projekcja właściwości ParentSeriesGroup.PieSplitBy. 2) Jeśli wartość właściwości to PieSplitType.Custom, możesz zdefiniować własne informacje podziału przy użyciu właściwości ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 % rozmiaru obszaru wykresu). To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu byte.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.DoughnutHoleSize.

**Zwraca:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Określa kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. W związku z tym własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.FirstSliceAngle odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja właściwości ParentSeriesGroup.FirstSliceAngle.

**Zwraca:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Niestandardowe informacje podziału dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. To jest własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Tylko do odczytu [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Jest to projekcja właściwości ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Jest to własność nie tylko tego szeregu, ale wszystkich szeregów grupy serii nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego ta własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj własności ParentSeriesGroup.BubbleSizeRepresentation odczyt/zapis, aby zmienić wartość.

--------------------

Jest to projekcja własności ParentSeriesGroup.BubbleSizeRepresentation.

**Zwraca:**
int