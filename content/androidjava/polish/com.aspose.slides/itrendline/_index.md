---
title: ITrendline
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
description: Klasa reprezentuje linię trendu serii wykresu
type: docs
url: /pl/com.aspose.slides/itrendline/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Klasa reprezentuje linię trendu serii wykresu
## Metody

| Metoda | Opis |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Pobiera lub ustawia nazwę linii trendu. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Pobiera lub ustawia nazwę linii trendu. |
| [getTrendlineType()](#getTrendlineType--) | Pobiera lub ustawia typ linii trendu. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Pobiera lub ustawia typ linii trendu. |
| [getFormat()](#getFormat--) | Reprezentuje format linii trendu. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje format linii trendu. |
| [getBackward()](#getBackward--) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga przed danymi serii, która jest trendowana. |
| [setBackward(double value)](#setBackward-double-) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga przed danymi serii, która jest trendowana. |
| [getForward()](#getForward--) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga po danych serii, która jest trendowana. |
| [setForward(double value)](#setForward-double-) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga po danych serii, która jest trendowana. |
| [getIntercept()](#getIntercept--) | Określa wartość, w której linia trendu przecina oś Y. |
| [setIntercept(double value)](#setIntercept-double-) | Określa wartość, w której linia trendu przecina oś Y. |
| [getDisplayEquation()](#getDisplayEquation--) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość R-kwadrat). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość R-kwadrat). |
| [getOrder()](#getOrder--) | Określa stopień wielomianowej linii trendu. |
| [setOrder(byte value)](#setOrder-byte-) | Określa stopień wielomianowej linii trendu. |
| [getPeriod()](#getPeriod--) | Określa okres linii trendu dla linii trendu średniej kroczącej. |
| [setPeriod(byte value)](#setPeriod-byte-) | Określa okres linii trendu dla linii trendu średniej kroczącej. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje pozycję legendy związaną z tą linią trendu Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Pobiera lub ustawia nazwę linii trendu. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Pobiera lub ustawia nazwę linii trendu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Pobiera lub ustawia typ linii trendu. Odczyt/zapis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Zwraca:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Pobiera lub ustawia typ linii trendu. Odczyt/zapis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje format linii trendu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Reprezentuje format linii trendu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga przed danymi serii, która jest trendowana. Na wykresach punktowych i nie-punktowych wartość może być dowolną nieujemną wartością. Odczyt/zapis double.

**Zwraca:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga przed danymi serii, która jest trendowana. Na wykresach punktowych i nie-punktowych wartość może być dowolną nieujemną wartością. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga po danych serii, która jest trendowana. Na wykresach punktowych i nie-punktowych wartość może być dowolną nie-ujemną wartością. Odczyt/zapis double.

**Zwraca:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), które linia trendu rozciąga po danych serii, która jest trendowana. Na wykresach punktowych i nie-punktowych wartość może być dowolną nie-ujemną wartością. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Określa wartość, w której linia trendu przecina oś Y. Właściwość ta jest obsługiwana tylko wtedy, gdy typ linii trendu to exp, linear lub poly. Odczyt/zapis double.

**Zwraca:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Określa wartość, w której linia trendu przecina oś Y. Właściwość ta jest obsługiwana tylko wtedy, gdy typ linii trendu to exp, linear lub poly. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość R-kwadrat). Odczyt/zapis boolean.

**Zwraca:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość R-kwadrat). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Określa stopień wielomianowej linii trendu. Jest ignorowany dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Odczyt/zapis byte.

**Zwraca:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Określa stopień wielomianowej linii trendu. Jest ignorowany dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Określa okres linii trendu dla linii trendu średniej kroczącej. Jest ignorowany dla innych wariantów linii trendu. Wartość musi mieścić się w przedziale od 2 do 255. Odczyt/zapis byte.

**Zwraca:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Określa okres linii trendu dla linii trendu średniej kroczącej. Jest ignorowany dla innych wariantów linii trendu. Wartość musi mieścić się w przedziale od 2 do 255. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Odczyt/zapis boolean.

**Zwraca:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje pozycję legendy związaną z tą linią trendu Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)