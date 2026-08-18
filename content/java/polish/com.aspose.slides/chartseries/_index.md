---
title: ChartSeries
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje serię wykresu.
type: docs
url: /pl/com.aspose.slides/chartseries/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Reprezentuje serię wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [getExplosion()](#getExplosion--) | Odległość otwartego wycinka tortu od środka wykresu kołowego wyrażona jest jako procent średnicy koła. |
| [setExplosion(int value)](#setExplosion-int-) | Odległość otwartego wycinka tortu od środka wykresu kołowego wyrażona jest jako procent średnicy koła. |
| [getSmooth()](#getSmooth--) | Reprezentuje wygładzanie krzywej. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Reprezentuje wygładzanie krzywej. |
| [getName()](#getName--) | Zwraca nazwę serii. |
| [getDataPoints()](#getDataPoints--) | Zwraca kolekcję punktów danych tej serii. |
| [getType()](#getType--) | Zwraca typ tej serii. |
| [setType(int value)](#setType-int-) | Zwraca typ tej serii. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy ta seria jest rysowana na drugorzędnej osi. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Wskazuje, czy ta seria jest rysowana na drugorzędnej osi. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Zwraca format serii. |
| [getOrder()](#getOrder--) | Zwraca kolejność serii. |
| [setOrder(int value)](#setOrder-int-) | Zwraca kolejność serii. |
| [getLabels()](#getLabels--) | Zwraca Labels serii. |
| [getTrendLines()](#getTrendLines--) | Kolekcja linii trendu serii. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Reprezentuje ErrorBars serii w kierunku X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Reprezentuje ErrorBars serii w kierunku Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje pozycję legendy związaną z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Określa kształt serii wykresu słupkowego 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Określa kształt serii wykresu słupkowego 3D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że seria słupków, kolumn lub bąbelków odwróci swoje kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że seria słupków, kolumn lub bąbelków odwróci swoje kolory, jeśli wartość jest ujemna. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Określa odwrócenie jednolitego koloru dla serii. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Reprezentuje wewnętrzne punkty. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Reprezentuje wewnętrzne punkty. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Reprezentuje punkty odstające. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Reprezentuje punkty odstające. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Reprezentuje znaczniki średniej. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Reprezentuje znaczniki średniej. |
| [getShowMeanLine()](#getShowMeanLine--) | Reprezentuje linię średniej. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Reprezentuje linię średniej. |
| [getQuartileMethod()](#getQuartileMethod--) | Reprezentuje metodę kwartylową. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Reprezentuje metodę kwartylową. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Reprezentuje linie łączące. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Reprezentuje linie łączące. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Reprezentuje układ etykiet nadrzędnych kategorii. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Reprezentuje układ etykiet nadrzędnych kategorii. |
| [hasUpDownBars()](#hasUpDownBars--) | Określa, czy wykres liniowy lub giełdowy ma słupki w górę/dół. |
| [getGapWidth()](#getGapWidth--) | Określa odstęp między grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, między seriami danych w wykresie 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Określa kąt pierwszego wycinka wykresu kołowego lub pączkowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pączkowym (może wynosić od 10% do 90% rozmiaru obszaru wykresu). |
| [getOverlap()](#getOverlap--) | Określa, o ile słupki i kolumny nakładają się na wykresach 2D, jako procent (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego koła lub słupka w wykresie koło-w-koło lub słupek-w-koło, jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Określa, czy istnieją linie serii dla tej serii i serii powiązanych. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informacje o niestandardowym podziale dla wykresu koło-w-koło lub słupek-w-koło z niestandardowym podziałem. |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0% do 300% domyślnego rozmiaru). |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną FillFormat. |

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

Odległość otwartego wycinka tortu od środka wykresu kołowego wyrażona jest jako procent średnicy koła. Odczyt/zapis int.

**Zwraca:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Odległość otwartego wycinka tortu od środka wykresu kołowego wyrażona jest jako procent średnicy koła. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Reprezentuje wygładzanie krzywej. True jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub rozrzutu. Ma zastosowanie tylko do wykresów liniowych i rozrzutu połączonych liniami. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Reprezentuje wygładzanie krzywej. True jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub rozrzutu. Ma zastosowanie tylko do wykresów liniowych i rozrzutu połączonych liniami. Odczyt/zapis boolean.

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

Wskazuje, czy ta seria jest rysowana na drugorzędnej osi. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Wskazuje, czy ta seria jest rysowana na drugorzędnej osi. Odczyt/zapis boolean.

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

Zwraca Labels serii. Tylko do odczytu [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Zwraca:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Kolekcja linii trendu serii. Tylko do odczytu [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines są dostępne (nie null) dla serii danych w nieskładowych wykresach obszarowych 2D, słupkowych, kolumnowych, liniowych, giełdowych, xy (rozrzutu) i bąbelkowych. Linia trendu nie jest dostępna dla serii danych w żadnym typie wykresu, który jest składowany lub 3D. TrendLines nie są również dostępne dla wykresów radarowych, kołowych, powierzchniowych ani pączkowych.

**Zwraca:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Reprezentuje ErrorBars serii w kierunku X. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars w kierunku X są dostępne dla serii typu area, bar, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje ErrorBars serii w kierunku Y. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars w kierunku Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje pozycję legendy związaną z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Określa kształt serii wykresu słupkowego 3D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Zwraca:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Określa kształt serii wykresu słupkowego 3D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Określa, że seria słupków, kolumn lub bąbelków odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Określa, że seria słupków, kolumn lub bąbelków odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

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
public final Color getAutomaticSeriesColor()
```

Zwraca automatyczny kolor serii oparty na indeksie serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined.

**Zwraca:**
java.awt.Color - Obiekt java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Reprezentuje punkty wewnętrzne. Prawda, jeśli punkty wewnętrzne są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Reprezentuje punkty wewnętrzne. Prawda, jeśli punkty wewnętrzne są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Reprezentuje linię średniej. Prawda, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Reprezentuje linię średniej. Prawda, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

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
| --- — | --- | --- |
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

Reprezentuje układ etykiet nadrzędnych kategorii. Dotyczy wyłącznie wykresów Treemap.

**Zwraca:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Reprezentuje układ etykiet nadrzędnych kategorii. Dotyczy wyłącznie wykresów Treemap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Określa, czy wykres liniowy lub giełdowy posiada słupki wartości rosnących/malejących. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars do formatowania słupków rosnących/malejących. Tylko do odczytu boolean.

--------------------

Jest to projekcja własności ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Zwraca:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Określa odstęp między grupami słupków lub kolumn, wyrażony procentowo względem szerokości słupka lub kolumny. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.GapWidth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.GapWidth.

**Zwraca:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Zwraca lub ustawia odległość, wyrażoną procentowo względem szerokości znacznika, między seriami danych w wykresie 3-D. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.GapDepth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.GapDepth.

**Zwraca:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Określa kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.FirstSliceAngle odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.FirstSliceAngle.

**Zwraca:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu byte.

--------------------

Jest to projekcja własności ParentSeriesGroup.DoughnutHoleSize.

**Zwraca:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Określa, w jakim stopniu słupki i kolumny nakładają się na wykresach 2-D, wyrażone procentowo (od -100 % do 100 %). To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych. Jest to projekcja odpowiedniej własności w grupie serii nadrzędnych, dlatego własność jest tylko do odczytu. Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap odczyt/zapis. Tylko do odczytu byte.

--------------------

Nakładanie określa stopień nachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
- -100 %: maksymalny odstęp (słupki są całkowicie rozdzielone).
- 0 %: słupki są ustawione obok siebie bez nachodzenia i bez odstępu.
- 100 %: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą).

Jest to projekcja własności ParentSeriesGroup.Overlap.

**Zwraca:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Określa rozmiar drugiego wycinka lub słupka wykresu kołowego-kołowego lub słupkowego-kołowego, wyrażony procentowo względem rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.SecondPieSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.SecondPieSize.

**Zwraca:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Określa, czy dla tej serii i powiązanych serii istnieją linie serii. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.HasSeriesLines odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat, aby sformatować linie serii. Tylko do odczytu boolean.

--------------------

Jest to projekcja własności ParentSeriesGroup.HasSeriesLines.

**Zwraca:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Określa, w jaki sposób wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.BubbleSizeRepresentation odczyt/zapis, aby zmienić wartość.

--------------------

Jest to projekcja własności ParentSeriesGroup.BubbleSizeRepresentation.

**Zwraca:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku wykresu kołowego-kołowego lub słupkowego-kołowego. Jest używana razem z własnością PieSplitBy. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.PieSplitPosition odczyt/zapis, aby zmienić wartość. Tylko do odczytu double.

--------------------

Jest to projekcja własności ParentSeriesGroup.PieSplitPosition.

**Zwraca:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Określa, w jaki sposób określić, które punkty danych znajdują się w drugim wycinku lub słupku wykresu kołowego-kołowego lub słupkowego-kołowego. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. W związku z tym własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj właściwości ParentSeriesGroup.PieSplitBy odczyt/zapis, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jest to projekcja własności ParentSeriesGroup.PieSplitBy. 2) Jeśli wartość własności to PieSplitType.Custom, możesz zdefiniować własne informacje podziału przy użyciu własności ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Dane podziału niestandardowego dla wykresu kołowego-kołowego lub słupkowego-kołowego z podziałem niestandardowym. Zawiera punkty danych, które mają być rysowane w drugim wycinku lub słupku wykresu kołowego-kołowego lub słupkowego-kołowego. To własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. Tylko do odczytu [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Jest to projekcja własności ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Określa, że każdy znacznik danych w serii ma inny kolor. Jest to własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. Dlatego ta własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj własności ParentSeriesGroup.IsColorVaried do odczytu/zapisu, aby zmienić wartość. Typ logiczny tylko do odczytu.

--------------------

Jest to projekcja własności ParentSeriesGroup.IsColorVaried.

**Zwraca:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 do 300 % domyślnego rozmiaru). Jest to własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnych – jest to projekcja odpowiedniej własności grupy. Dlatego ta własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych. Użyj własności ParentSeriesGroup.BubbleSizeScale do odczytu/zapisu, aby zmienić wartość.

--------------------

Jest to projekcja własności ParentSeriesGroup.BubbleSizeScale.

**Zwraca:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca nadrzędny slajd obiektu FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca nadrzędną prezentację obiektu FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)