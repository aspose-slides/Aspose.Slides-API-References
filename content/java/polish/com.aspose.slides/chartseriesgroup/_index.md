---
title: ChartSeriesGroup
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje grupę serii.
type: docs
url: /pl/com.aspose.slides/chartseriesgroup/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Reprezentuje grupę serii.

--------------------

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.
## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca typ tej grupy serii. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy seria tej grupy jest rysowana na drugiej osi. |
| [getSeries()](#getSeries--) | Zwraca kolekcję serii. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [getUpDownBars()](#getUpDownBars--) | Zapewnia dostęp do słupków góra/dół wykresu liniowego lub świecowego. |
| [getGapWidth()](#getGapWidth--) | Pobiera lub ustawia odstęp między grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. |
| [setGapWidth(int value)](#setGapWidth-int-) | Pobiera lub ustawia odstęp między grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Pobiera lub ustawia odległość między seriami danych w wykresie 3D jako procent szerokości znacznika. |
| [setGapDepth(int value)](#setGapDepth-int-) | Pobiera lub ustawia odległość między seriami danych w wykresie 3D jako procent szerokości znacznika. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu.). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu.). |
| [getOverlap()](#getOverlap--) | Określa, jak bardzo słupki i kolumny mają na siebie zachodzić w wykresach 2D, jako procent (od -100% do 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Określa, jak bardzo słupki i kolumny mają na siebie zachodzić w wykresach 2D, jako procent (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego koła lub słupka w wykresie koło-w-kwadracie lub słupek-w-kwadracie jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Określa rozmiar drugiego koła lub słupka w wykresie koło-w-kwadracie lub słupek-w-kwadracie jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [hasSeriesLines()](#hasSeriesLines--) | Prawda, jeśli wykres ma linie serii. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Prawda, jeśli wykres ma linie serii. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Określa format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informacje o niestandardowym podziale dla wykresu koło-w-kwadracie lub słupek-w-kwadracie z niestandardowym podziałem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny obiektu FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną obiektu FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Zwraca typ tej grupy serii. Tylko do odczytu [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Zwraca:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Wskazuje, czy seria tej grupy jest rysowana na drugiej osi. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Zwraca kolekcję serii. Tylko do odczytu [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Zwraca:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Pobiera element o określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Zapewnia dostęp do słupków góra/dół wykresu liniowego lub świecowego. Tylko do odczytu [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Zwraca:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Pobiera lub ustawia odstęp między grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. Wartość musi wynosić od 0 do 500. Odczyt/zapis int.

--------------------

Ta właściwość ma zastosowanie do serii następujących typów: podtypy Bar (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), podtypy Column (zobacz także metodę [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Zwraca:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Pobiera lub ustawia odstęp między grupami słupków lub kolumn jako procent szerokości słupka lub kolumny. Wartość musi wynosić od 0 do 500. Odczyt/zapis int.

--------------------

Ta właściwość ma zastosowanie do serii następujących typów: podtypy Bar (zobacz także metodę [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), podtypy Column (zobacz także metodę [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Pobiera lub ustawia odległość między seriami danych w wykresie 3D jako procent szerokości znacznika. Wartość musi wynosić od 0 do 500. Odczyt/zapis int.

--------------------

Ta właściwość ma zastosowanie do serii następujących typów: podtypy 3D bar i column (zobacz także metodę [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Zwraca:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Pobiera lub ustawia odległość między seriami danych w wykresie 3D jako procent szerokości znacznika. Wartość musi wynosić od 0 do 500. Odczyt/zapis int.

--------------------

Ta właściwość ma zastosowanie do serii następujących typów: podtypy 3D bar i column (zobacz także metodę [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis int.

**Zwraca:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis byte.

**Zwraca:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Określa, jak bardzo słupki i kolumny mają na siebie zachodzić w wykresach 2D, jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie rozdzielone). - 0%: słupki są ustawione obok siebie bez zachodzenia ani odstępu. - 100%: maksymalne zachodzenie (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nakładanie na 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Określa, jak bardzo słupki i kolumny mają na siebie zachodzić w wykresach 2D, jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie rozdzielone). - 0%: słupki są ustawione obok siebie bez zachodzenia ani odstępu. - 100%: maksymalne zachodzenie (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nakładanie na 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Określa rozmiar drugiego koła lub słupka w wykresie koło-w-kwadracie lub słupek-w-kwadracie jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). Odczyt/zapis int.

**Zwraca:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Określa rozmiar drugiego koła lub słupka w wykresie koło-w-kwadracie lub słupek-w-kwadracie jako procent rozmiaru pierwszego koła (może wynosić od 5% do 200%). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Odczyt/zapis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Zwraca:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Odczyt/zapis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. Jest używana razem z własnością PieSplitBy. Odczyt/zapis double.

**Zwraca:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. Jest używana razem z własnością PieSplitBy. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. Odczyt/zapis [PieSplitType](../../com.aspose.slides/piesplittype).

**Zwraca:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. Odczyt/zapis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Prawda, jeśli wykres ma linie serii. Stosowane do wykresów stacked bar i OfPie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Prawda, jeśli wykres ma linie serii. Stosowane do wykresów stacked bar i OfPie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose.

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis int.

**Zwraca:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informacje o niestandardowym podziale dla wykresu koło-w-kwadracie lub słupek-w-kwadracie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie koło-w-kwadracie lub słupek-w-kwadracie. Tylko do odczytu [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Zwraca:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
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
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny obiektu FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną obiektu FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)