---
title: IErrorBarsFormat
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Reprezentuje słupki błędów serii wykresu.
type: docs
url: /pl/com.aspose.slides/ierrorbarsformat/
---
**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Reprezentuje słupki błędów serii wykresu. Niestandardowe wartości ErrorBars znajdują się w IChartDataPointCollection (w własności [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Pobiera lub ustawia typ słupków błędów. |
| [setType(int value)](#setType-int-) | Pobiera lub ustawia typ słupków błędów. |
| [getValueType()](#getValueType--) | Reprezentuje możliwe sposoby określenia długości słupków błędów. |
| [setValueType(int value)](#setValueType-int-) | Reprezentuje możliwe sposoby określenia długości słupków błędów. |
| [hasEndCap()](#hasEndCap--) | Określa, że zakończenie nie jest rysowane na słupkach błędów. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Określa, że zakończenie nie jest rysowane na słupkach błędów. |
| [getValue()](#getValue--) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. |
| [setValue(float value)](#setValue-float-) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. |
| [getFormat()](#getFormat--) | Reprezentuje format słupków błędów. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje format słupków błędów. |
| [isVisible()](#isVisible--) | Pobiera lub ustawia widoczność słupków błędów. |
| [setVisible(boolean value)](#setVisible-boolean-) | Pobiera lub ustawia widoczność słupków błędów. |

### getType() {#getType--}
```
public abstract int getType()
```

Pobiera lub ustawia typ słupków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Pobiera lub ustawia typ słupków błędów. Odczyt/zapis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Reprezentuje możliwe sposoby określenia długości słupków błędów. W przypadku typu niestandardowego, aby określić wartość, użyj własności [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkretnego punktu danych w kolekcji DataPoints serii. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Zwraca:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Reprezentuje możliwe sposoby określenia długości słupków błędów. W przypadku typu niestandardowego, aby określić wartość, użyj własności [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkretnego punktu danych w kolekcji DataPoints serii. Odczyt/zapis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Określa, że zakończenie nie jest rysowane na słupkach błędów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Określa, że zakończenie nie jest rysowane na słupkach błędów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. Odczyt/zapis float.

**Zwraca:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje format słupków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Reprezentuje format słupków błędów. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Pobiera lub ustawia widoczność słupków błędów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Pobiera lub ustawia widoczność słupków błędów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |