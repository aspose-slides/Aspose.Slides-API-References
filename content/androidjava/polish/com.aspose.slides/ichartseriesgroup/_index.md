---
title: IChartSeriesGroup
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje grupę serii.
type: docs
url: /pl/com.aspose.slides/ichartseriesgroup/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Reprezentuje grupę serii.

--------------------

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („series group properties”). „Series group properties” w klasie ChartSeriesGroup jest odczyt/zapis. Każda z „series group properties” może mieć projekcję tylko do odczytu w klasie ChartSeries.

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca typ tej grupy serii. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Wskazuje, czy seria tej grupy jest rysowana na drugiej osi. |
| [getSeries()](#getSeries--) | Zwraca kolekcję serii wykresu tylko do odczytu. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [getUpDownBars()](#getUpDownBars--) | Zapewnia dostęp do słupków góra/dół wykresu liniowego lub giełdowego. |
| [getGapWidth()](#getGapWidth--) | Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. |
| [setGapWidth(int value)](#setGapWidth-int-) | Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. |
| [getGapDepth()](#getGapDepth--) | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). |
| [isColorVaried()](#isColorVaried--) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Określa, że każdy znacznik danych w serii ma inny kolor. |
| [hasSeriesLines()](#hasSeriesLines--) | Prawda, jeśli wykres ma linie serii. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Prawda, jeśli wykres ma linie serii. |
| [getOverlap()](#getOverlap--) | Określa, jak bardzo słupki i kolumny mają nakładać się na wykresach 2-D, wyrażone jako procent (od -100% do 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Określa, jak bardzo słupki i kolumny mają nakładać się na wykresach 2-D, wyrażone jako procent (od -100% do 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Określa rozmiar drugiego koła lub słupka wykresu koło-w-koło lub słupek-w-koło, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Określa rozmiar drugiego koła lub słupka wykresu koło-w-koło lub słupek-w-koło, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Określa wartość służącą do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Określa wartość służącą do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [getPieSplitBy()](#getPieSplitBy--) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informacje o niestandardowym podziale dla wykresu koło-w-koło lub słupek-w-koło z niestandardowym podziałem. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Określa format HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. |

### getType() {#getType--}
```
public abstract int getType()
```

Zwraca typ tej grupy serii. Tylko do odczytu [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Zwraca:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Wskazuje, czy seria tej grupy jest rysowana na drugiej osi. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Zwraca kolekcję serii wykresu tylko do odczytu. Tylko do odczytu [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Zwraca:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Zapewnia dostęp do słupków góra/dół wykresu liniowego lub giełdowego. Tylko do odczytu [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Zwraca:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. Odczyt/zapis int.

**Zwraca:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczyt/zapis int.

**Zwraca:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis int.

**Zwraca:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Prawda, jeśli wykres ma linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Prawda, jeśli wykres ma linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Określa, jak bardzo słupki i kolumny mają nakładać się na wykresach 2-D, wyrażone jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są ustawione obok siebie bez nakładania i bez odstępu. - 100%: maksymalny nakład (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nakład na 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Określa, jak bardzo słupki i kolumny mają nakładać się na wykresach 2-D, wyrażone jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są ustawione obok siebie bez nakładania i bez odstępu. - 100%: maksymalny nakład (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ustaw nakład na 55%
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
public abstract int getSecondPieSize()
```

Określa rozmiar drugiego koła lub słupka wykresu koło-w-koło lub słupek-w-koło, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). Odczyt/zapis int.

**Zwraca:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Określa rozmiar drugiego koła lub słupka wykresu koło-w-koło lub słupek-w-koło, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Określa wartość służącą do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. Jest używana razem z właściwością PieSplitBy. Odczyt/zapis double.

**Zwraca:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Określa wartość służącą do określenia, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. Jest używana razem z właściwością PieSplitBy. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. Odczyt/zapis [PieSplitType](../../com.aspose.slides/piesplittype).

**Zwraca:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. Odczyt/zapis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informacje o niestandardowym podziale dla wykresu koło-w-koło lub słupek-w-koło z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie koło-w-koło lub słupek-w-koło. Tylko do odczytu [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Zwraca:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis byte.

**Zwraca:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis int.

**Zwraca:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose.

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Odczyt/zapis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Zwraca:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Odczyt/zapis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |