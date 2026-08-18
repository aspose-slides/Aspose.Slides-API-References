---
title: IErrorBarsFormat
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje słupki błędów serii wykresu.
type: docs
url: /pl/com.aspose.slides/ierrorbarsformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Reprezentuje słupki błędów serii wykresu. Niestandardowe wartości ErrorBars znajdują się w IChartDataPointCollection (w właściwości [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Pobiera lub ustawia typ pasków błędów. |
| [setType(int value)](#setType-int-) | Pobiera lub ustawia typ pasków błędów. |
| [getValueType()](#getValueType--) | Reprezentuje możliwe sposoby określenia długości pasków błędów. |
| [setValueType(int value)](#setValueType-int-) | Reprezentuje możliwe sposoby określenia długości pasków błędów. |
| [hasEndCap()](#hasEndCap--) | Określa, że końcówka nie jest rysowana na paskach błędów. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Określa, że końcówka nie jest rysowana na paskach błędów. |
| [getValue()](#getValue--) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości pasków błędów. |
| [setValue(float value)](#setValue-float-) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości pasków błędów. |
| [getFormat()](#getFormat--) | Reprezentuje format pasków błędów. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje format pasków błędów. |
| [isVisible()](#isVisible--) | Pobiera lub ustawia widoczność pasków błędów. |
| [setVisible(boolean value)](#setVisible-boolean-) | Pobiera lub ustawia widoczność pasków błędów. |

### getType() {#getType--}
```
public abstract int getType()
```

Pobiera lub ustawia typ pasków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Pobiera lub ustawia typ pasków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Reprezentuje możliwe sposoby określenia długości pasków błędów. W przypadku niestandardowego typu wartości, aby określić wartość, użyj właściwości [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) określonego punktu danych w kolekcji DataPoints serii. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Zwraca:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Reprezentuje możliwe sposoby określenia długości pasków błędów. W przypadku niestandardowego typu wartości, aby określić wartość, użyj właściwości [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) określonego punktu danych w kolekcji DataPoints serii. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Określa, że końcówka nie jest rysowana na paskach błędów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Określa, że końcówka nie jest rysowana na paskach błędów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości pasków błędów. Odczyt/zapis float.

**Zwraca:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości pasków błędów. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje format pasków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Reprezentuje format pasków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Pobiera lub ustawia widoczność pasków błędów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Pobiera lub ustawia widoczność pasków błędów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |