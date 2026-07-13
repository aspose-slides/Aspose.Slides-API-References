---
title: IChartSeries
second_title: Aspose.Slides dla Androida – dokumentacja API Java
description: Reprezentuje serię wykresu.
type: docs
url: /pl/com.aspose.slides/ichartseries/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.
## Metody

| Metoda | Opis |
| --- | --- |
| [getExplosion()](#getExplosion--) | Odległość otwartego fragmentu wykresu kołowego od środka wykresu wyrażana jest jako procent średnicy koła. |
| [setExplosion(int value)](#setExplosion-int-) | Odległość otwartego fragmentu wykresu kołowego od środka wykresu wyrażana jest jako procent średnicy koła. |
| [getSmooth()](#getSmooth--) | Reprezentuje wygładzanie krzywej. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Reprezentuje wygładzanie krzywej. |
| [getMarker()](#getMarker--) | Zwraca znacznik serii. |
| [getBar3DShape()](#getBar3DShape--) | Określa kształt serii wykresu słupkowego 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Określa kształt serii wykresu słupkowego 3D. |
| [getName()](#getName--) | Zwraca nazwę serii. |
| [getDataPoints()](#getDataPoints--) | Zwraca kolekcję punktów danych tej serii. |
| [getType()](#getType--) | Zwraca typ tej serii. |
| [setType(int value)](#setType-int-) | Zwraca typ tej serii. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Zwraca grupę serii nadrzędną. |
| [getFormat()](#getFormat--) | Zwraca format serii. |
| [getOrder()](#getOrder--) | Zwraca kolejność serii. |
| [setOrder(int value)](#setOrder-int-) | Zwraca kolejność serii. |
| [getLabels()](#getLabels--) | Zwraca etykiety serii. |
| [getTrendLines()](#getTrendLines--) | Kolekcja linii trendu serii Tylko do odczytu [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Reprezentuje paski błędów serii w kierunku X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Reprezentuje paski błędów serii w kierunku Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy ta seria jest rysowana na drugiej osi wartości. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Wskazuje, czy ta seria jest rysowana na drugiej osi wartości. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Zwraca lub ustawia format liczbowy dla wartości serii. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Zwraca lub ustawia format liczbowy dla wartości serii. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Zwraca lub ustawia format liczbowy dla wartości X serii. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Zwraca lub ustawia format liczbowy dla wartości X serii. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Zwraca lub ustawia format liczbowy dla wartości Y serii. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Zwraca lub ustawia format liczbowy dla wartości Y serii. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Zwraca lub ustawia format liczbowy dla rozmiarów bąbelków serii. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Zwraca lub ustawia format liczbowy dla rozmiarów bąbelków serii. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Określa odwrócony jednolity kolor dla serii. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje wpis legendy powiązany z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
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
| [getParentLabelLayout()](#getParentLabelLayout--) | Reprezentuje układ etykiet kategorii nadrzędnej. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Reprezentuje układ etykiet kategorii nadrzędnej. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [hasUpDownBars()](#hasUpDownBars--) | Określa, czy wykres liniowy lub giełdowy posiada słupki góra/dół. |
| [getGapWidth()](#getGapWidth--) | Określa odstęp pomiędzy grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Zwraca lub ustawia odległość, wyrażoną w procentach szerokości markera, między seriami danych w wykresie 3D. |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [hasSeriesLines()](#hasSeriesLines--) | Określa, czy istnieją linie serii dla tej serii i pokrewnych serii. |
| [getOverlap()](#getOverlap--) | Określa, o ile słupki i kolumny zachodzą na siebie w wykresach 2D, wyrażone w procentach (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego koła lub słupka wykresu koło-w-kręgu lub słupek-w-kręgu, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kręgu lub słupek-w-kręgu. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kręgu lub słupek-w-kręgu. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Określa kąt pierwszego fragmentu wykresu kołowego lub pierścieniowego, w stopniach (z rotacją zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Niestandardowe informacje o podziale dla wykresu koło-w-kręgu lub słupek-w-kręgu z niestandardowym podziałem. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa, jak wartości rozmiaru bąbelków są przedstawiane na wykresie bąbelkowym. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Odległość otwartego fragmentu wykresu kołowego od środka wykresu wyrażana jest jako procent średnicy koła. Odczyt/zapis int.

**Zwraca:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Odległość otwartego fragmentu wykresu kołowego od środka wykresu wyrażana jest jako procent średnicy koła. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Reprezentuje wygładzanie krzywej. Prawda, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub punktowego. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Reprezentuje wygładzanie krzywej. Prawda, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub punktowego. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis boolean.

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

Określa kształt serii wykresu słupkowego 3D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Zwraca:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Określa kształt serii wykresu słupkowego 3D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [ChartShapeType](../../com.aspose.slides/chartshapetype).

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

Zwraca grupę serii nadrzędną. Tylko do odczytu [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

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

Reprezentuje paski błędów serii w kierunku X. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje paski błędów serii w kierunku Y. Tylko do odczytu [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Zwraca:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Wskazuje, czy ta seria jest rysowana na drugiej osi wartości. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Wskazuje, czy ta seria jest rysowana na drugiej osi wartości. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Zwraca lub ustawia format liczbowy dla wartości serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Zwraca lub ustawia format liczbowy dla wartości serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Zwraca lub ustawia format liczbowy dla wartości X serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Zwraca lub ustawia format liczbowy dla wartości X serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Zwraca lub ustawia format liczbowy dla wartości Y serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Zwraca lub ustawia format liczbowy dla wartości Y serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Zwraca lub ustawia format liczbowy dla rozmiarów bąbelków serii. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Zwraca lub ustawia format liczbowy dla rozmiarów bąbelków serii. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Określa, że seria słupków, kolumn lub bąbelków odwróci kolory, jeśli wartość jest ujemna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Określa odwrócony jednolity kolor dla serii. Aby zastosować ustawienie koloru, ustaw format serii FillType na FillType.Solid. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje wpis legendy powiązany z tą serią Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined.

**Zwraca:**
java.lang.Integer - Automatic color of series java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Reprezentuje znaczniki średniej. Prawda, jeśli linia średniej jest wyświetlana w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Reprezentuje znaczniki średniej. Prawda, jeśli linia średniej jest wyświetlana w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Reprezentuje metodę kwartylu. Dotyczy wyłącznie wykresów BoxAndWhisker.

**Zwraca:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Reprezentuje metodę kwartylu. Dotyczy wyłącznie wykresów BoxAndWhisker.

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

Reprezentuje układ etykiet kategorii nadrzędnej. Dotyczy wyłącznie wykresów Treemap.

**Zwraca:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Reprezentuje układ etykiet kategorii nadrzędnej. Dotyczy wyłącznie wykresów Treemap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeScale odczyt/zapis, aby zmienić wartość.

--------------------

Jest to projekcja własności ParentSeriesGroup.BubbleSizeScale.

**Zwraca:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Określa, czy wykres liniowy lub giełdowy posiada słupki góra/dół. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars, aby sformatować słupki góra/dół. Tylko do odczytu boolean.

--------------------

Jest to projekcja własności ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Zwraca:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Określa odstęp pomiędzy grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.GapWidth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.GapWidth.

**Zwraca:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Zwraca lub ustawia odległość, wyrażoną w procentach szerokości markera, między seriami danych w wykresie 3D. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.GapDepth odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.GapDepth.

**Zwraca:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.IsColorVaried odczyt/zapis, aby zmienić wartość. Tylko do odczytu boolean.

--------------------

Jest to projekcja własności ParentSeriesGroup.IsColorVaried.

**Zwraca:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Określa, czy istnieją linie serii dla tej serii i pokrewnych serii. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.HasSeriesLines odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat, aby sformatować linie serii. Tylko do odczytu boolean.

--------------------

Jest to projekcja własności ParentSeriesGroup.HasSeriesLines.

**Zwraca:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Określa, o ile słupki i kolumny zachodzą na siebie w wykresach 2D, wyrażone w procentach (od -100% do 100%). To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej. Jest to projekcja odpowiedniej własności w grupie nadrzędnej, dlatego własność jest tylko do odczytu. Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap odczyt/zapis. Tylko do odczytu byte.

--------------------

Overlap określa stopień zachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
- 100%: maksymalny odstęp (słupki są całkowicie rozdzielone).
0%: słupki są obok siebie bez zachodzenia ani odstępu.
100%: maksymalne zachodzenie (słupki całkowicie na siebie nachodzą). To jest projekcja własności ParentSeriesGroup.Overlap.

**Zwraca:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Określa rozmiar drugiego koła lub słupka wykresu koło-w-kręgu lub słupek-w-kręgu, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.SecondPieSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.SecondPieSize.

**Zwraca:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kręgu lub słupek-w-kręgu. Jest używana razem z własnością PieSplitBy. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitPosition odczyt/zapis, aby zmienić wartość. Tylko do odczytu double.

--------------------

Jest to projekcja własności ParentSeriesGroup.PieSplitPosition.

**Zwraca:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kręgu lub słupek-w-kręgu. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitBy odczyt/zapis, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jest to projekcja własności ParentSeriesGroup.PieSplitBy. 2) Jeśli wartość własności to PieSplitType.Custom, możesz określić niestandardowe informacje o podziale przy pomocy właściwości ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu byte.

--------------------

Jest to projekcja własności ParentSeriesGroup.DoughnutHoleSize.

**Zwraca:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Określa kąt pierwszego fragmentu wykresu kołowego lub pierścieniowego, w stopniach (z rotacją zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.FirstSliceAngle odczyt/zapis, aby zmienić wartość. Tylko do odczytu int.

--------------------

Jest to projekcja własności ParentSeriesGroup.FirstSliceAngle.

**Zwraca:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Niestandardowe informacje o podziale dla wykresu koło-w-kręgu lub słupek-w-kręgu z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie koło-w-kręgu lub słupek-w-kręgu. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Tylko do odczytu [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Jest to projekcja własności ParentSeriesGroup.PieSplitCustomPoints.

**Zwraca:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Określa, jak wartości rozmiaru bąbelków są przedstawiane na wykresie bąbelkowym. To jest własność nie tylko tej serii, ale wszystkich serii grupy nadrzędnej – jest to projekcja odpowiedniej własności grupy. Dlatego własność jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeRepresentation odczyt/zapis, aby zmienić wartość.

--------------------

Jest to projekcja własności ParentSeriesGroup.BubbleSizeRepresentation.

**Zwraca:**
int