---
title: ErrorBarsFormat
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje słupki błędu serii wykresu.
type: docs
url: /pl/com.aspose.slides/errorbarsformat/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Reprezentuje słupki błędu serii wykresu. Niestandardowe wartości ErrorBars znajdują się w IChartDataPointCollection (w własności ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Pobiera lub ustawia typ słupków błędu. |
| [setType(int value)](#setType-int-) | Pobiera lub ustawia typ słupków błędu. |
| [getValueType()](#getValueType--) | Reprezentuje możliwe sposoby określenia długości słupków błędu. |
| [setValueType(int value)](#setValueType-int-) | Reprezentuje możliwe sposoby określenia długości słupków błędu. |
| [hasEndCap()](#hasEndCap--) | Określa, że końcowa nasadka nie jest rysowana na słupkach błędu. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Określa, że końcowa nasadka nie jest rysowana na słupkach błędu. |
| [getValue()](#getValue--) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędu. |
| [setValue(float value)](#setValue-float-) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędu. |
| [getFormat()](#getFormat--) | Reprezentuje format słupków błędu. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje format słupków błędu. |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [isVisible()](#isVisible--) | Pobiera lub ustawia widoczność słupków błędu. |
| [setVisible(boolean value)](#setVisible-boolean-) | Pobiera lub ustawia widoczność słupków błędu. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny dla FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną dla FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Pobiera lub ustawia typ słupków błędu. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Zwraca:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Pobiera lub ustawia typ słupków błędu. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Reprezentuje możliwe sposoby określenia długości słupków błędu. W przypadku typu niestandardowego użyj własności ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) określonego punktu danych w kolekcji DataPoints serii. W przypadku typów Fixed, Percentage lub StandardDeviation użyj własności Value, aby określić wartość. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Zwraca:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Reprezentuje możliwe sposoby określenia długości słupków błędu. W przypadku typu niestandardowego użyj własności ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) określonego punktu danych w kolekcji DataPoints serii. W przypadku typów Fixed, Percentage lub StandardDeviation użyj własności Value, aby określić wartość. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Określa, że końcowa nasadka nie jest rysowana na słupkach błędu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Określa, że końcowa nasadka nie jest rysowana na słupkach błędu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędu. W każdym innym przypadku zwróci NaN. Odczyt/zapis float.

**Zwraca:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędu. W każdym innym przypadku zwróci NaN. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje format słupków błędu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje format słupków błędu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Pobiera lub ustawia widoczność słupków błędu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Pobiera lub ustawia widoczność słupków błędu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny dla FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną dla FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)