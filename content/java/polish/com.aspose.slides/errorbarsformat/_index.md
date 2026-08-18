---
title: ErrorBarsFormat
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje słupki błędów serii wykresu.
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

Reprezentuje słupki błędów serii wykresu. Niestandardowe wartości ErrorBars znajdują się w IChartDataPointCollection (w właściwości ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Pobiera lub ustawia typ słupków błędów. |
| [setType(int value)](#setType-int-) | Pobiera lub ustawia typ słupków błędów. |
| [getValueType()](#getValueType--) | Reprezentuje możliwe sposoby określenia długości słupków błędów. |
| [setValueType(int value)](#setValueType-int-) | Reprezentuje możliwe sposoby określenia długości słupków błędów. |
| [hasEndCap()](#hasEndCap--) | Określa, że na końcach słupków błędów nie jest rysowany daszek. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Określa, że na końcach słupków błędów nie jest rysowany daszek. |
| [getValue()](#getValue--) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. |
| [setValue(float value)](#setValue-float-) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. |
| [getFormat()](#getFormat--) | Reprezentuje format słupków błędów. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje format słupków błędów. |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [isVisible()](#isVisible--) | Pobiera lub ustawia widoczność słupków błędów. |
| [setVisible(boolean value)](#setVisible-boolean-) | Pobiera lub ustawia widoczność słupków błędów. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny obiektu FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną obiektu FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Pobiera lub ustawia typ słupków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Pobiera lub ustawia typ słupków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Reprezentuje możliwe sposoby określenia długości słupków błędów. W przypadku niestandardowego typu wartości, aby określić wartość, użyj własności ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkretnego punktu danych w kolekcji DataPoints serii. W przypadku typów wartości Fixed, Percentage lub StandardDeviation użyj własności Value, aby określić wartość. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Zwraca:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Reprezentuje możliwe sposoby określenia długości słupków błędów. W przypadku niestandardowego typu wartości, aby określić wartość, użyj własności ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkretnego punktu danych w kolekcji DataPoints serii. W przypadku typów wartości Fixed, Percentage lub StandardDeviation użyj własności Value, aby określić wartość. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Określa, że na końcach słupków błędów nie jest rysowany daszek. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Określa, że na końcach słupków błędów nie jest rysowany daszek. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. W każdym innym przypadku zwróci NaN. Odczyt/zapis float.

**Zwraca:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. W każdym innym przypadku zwróci NaN. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje format słupków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje format słupków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

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

Pobiera lub ustawia widoczność słupków błędów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Pobiera lub ustawia widoczność słupków błędów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

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