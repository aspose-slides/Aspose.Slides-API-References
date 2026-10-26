---
title: ChartSeriesGroup
second_title: Aspose.Slides dla Java – odniesienie API
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

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection i wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są do odczytu i zapisu. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca typ tej grupy serii. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy serie tej grupy są rysowane na drugorzędnej osi. |
| [getSeries()](#getSeries--) | Zwraca kolekcję serii. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [getUpDownBars()](#getUpDownBars--) | Zapewnia dostęp do pasków góra/dół wykresu liniowego lub akcji. |
| [getGapWidth()](#getGapWidth--) | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. |
| [setGapWidth(int value)](#setGapWidth-int-) | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Zwraca lub ustawia odległość, jako procent szerokości markera, pomiędzy seriami danych w wykresie 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Zwraca lub ustawia odległość, jako procent szerokości markera, pomiędzy seriami danych w wykresie 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). |
| [getOverlap()](#getOverlap--) | Określa, w jakim stopniu słupki i kolumny mają zachodzić na siebie w wykresach 2-D, jako procent (od -100% do 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Określa, w jakim stopniu słupki i kolumny mają zachodzić na siebie w wykresach 2-D, jako procent (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego wycinka lub słupka w wykresie kołowy-w-kołowym lub słupkowo-kołowym, jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Określa rozmiar drugiego wycinka lub słupka w wykresie kołowy-w-kołowym lub słupkowo-kołowym, jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa sposób określania, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Określa sposób określania, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [hasSeriesLines()](#hasSeriesLines--) | Prawda, jeśli wykres ma linie serii. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Prawda, jeśli wykres ma linie serii. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Określa format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informacje o niestandardowym podziale dla wykresu kołowy-w-kołowym lub słupkowo-kołowego z niestandardowym podziałem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Zwraca nadrzędny wykres. |
| [getSlide()](#getSlide--) | Zwraca nadrzędny slajd obiektu FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca nadrzędną prezentację obiektu FillFormat. |

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

Wskazuje, czy serie tej grupy są rysowane na drugorzędnej osi. Tylko do odczytu boolean.

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

Pobiera element o podanym indeksie.

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

Zapewnia dostęp do pasków góra/dół wykresu liniowego lub akcji. Tylko do odczytu [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Zwraca:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Do odczytu i zapisu int.

**Zwraca:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Zwraca lub ustawia odległość, jako procent szerokości markera, pomiędzy seriami danych w wykresie 3D. Do odczytu i zapisu int.

**Zwraca:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Zwraca lub ustawia odległość, jako procent szerokości markera, pomiędzy seriami danych w wykresie 3D. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Do odczytu i zapisu int.

**Zwraca:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). Do odczytu i zapisu byte.

**Zwraca:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). Do odczytu i zapisu byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Określa, w jakim stopniu słupki i kolumny mają zachodzić na siebie w wykresach 2-D, jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są rozmieszczone obok siebie bez nachodzenia i bez odstępu. - 100%: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą). Ta właściwość jest do odczytu i zapisu byte.

--------------------

> ```markdown
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nachodzenie na 55%
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

Określa, w jakim stopniu słupki i kolumny mają zachodzić na siebie w wykresach 2-D, jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są rozmieszczone obok siebie bez nachodzenia i bez odstępu. - 100%: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą). Ta właściwość jest do odczytu i zapisu byte.

--------------------

> ```markdown
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nachodzenie na 55%
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

Określa rozmiar drugiego wycinka lub słupka w wykresie kołowy-w-kołowym lub słupkowo-kołowym, jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). Do odczytu i zapisu int.

**Zwraca:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Określa rozmiar drugiego wycinka lub słupka w wykresie kołowy-w-kołowym lub słupkowo-kołowym, jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Do odczytu i zapisu [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Zwraca:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Do odczytu i zapisu [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. Jest używana razem z właściwością PieSplitBy. Do odczytu i zapisu double.

**Zwraca:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. Jest używana razem z właściwością PieSplitBy. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Określa sposób określania, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. Do odczytu i zapisu [PieSplitType](../../com.aspose.slides/piesplittype).

**Zwraca:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Określa sposób określania, które punkty danych znajdują się w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. Do odczytu i zapisu [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. Do odczytu i zapisu boolean.

**Zwraca:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Określa, że każdy znacznik danych w serii ma inny kolor. Do odczytu i zapisu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Prawda, jeśli wykres ma linie serii. Stosowane do wykresów słupkowych układanych i OfPie. Do odczytu i zapisu boolean.

**Zwraca:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Prawda, jeśli wykres ma linie serii. Stosowane do wykresów słupkowych układanych i OfPie. Do odczytu i zapisu boolean.

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

Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Do odczytu i zapisu int.

**Zwraca:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informacje o niestandardowym podziale dla wykresu kołowy-w-kołowym lub słupkowo-kołowego z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wycinku lub słupku w wykresie kołowy-w-kołowym lub słupkowo-kołowym. Tylko do odczytu [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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

Zwraca nadrzędny wykres. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)

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