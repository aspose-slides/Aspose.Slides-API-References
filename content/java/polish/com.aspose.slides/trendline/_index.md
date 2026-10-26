---
title: Trendline
second_title: Odwołanie do API Aspose.Slides dla Java
description: Klasa reprezentuje linię trendu serii wykresu
type: docs
url: /pl/com.aspose.slides/trendline/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
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
| [getBackward()](#getBackward--) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana przed danymi serii. |
| [setBackward(double value)](#setBackward-double-) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana przed danymi serii. |
| [getForward()](#getForward--) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana po danych serii. |
| [setForward(double value)](#setForward-double-) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana po danych serii. |
| [getIntercept()](#getIntercept--) | Określa wartość, w której linia trendu przecina oś Y. |
| [setIntercept(double value)](#setIntercept-double-) | Określa wartość, w której linia trendu przecina oś Y. |
| [getDisplayEquation()](#getDisplayEquation--) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tym samym etykiecie co wartość R-kwadrat). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tym samym etykiecie co wartość R-kwadrat). |
| [getOrder()](#getOrder--) | Określa stopień wielomianowej linii trendu. |
| [setOrder(byte value)](#setOrder-byte-) | Określa stopień wielomianowej linii trendu. |
| [getPeriod()](#getPeriod--) | Określa okres linii trendu dla średniej ruchomej. |
| [setPeriod(byte value)](#setPeriod-byte-) | Określa okres linii trendu dla średniej ruchomej. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tym samym etykiecie co równanie). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tym samym etykiecie co równanie). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje pozycję legendy związaną z tą linią trendu. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Może zawierać sformatowany tekst. |
| [getTextFormat()](#getTextFormat--) | Zwraca format tekstu. |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny formatu wypełnienia. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną formatu wypełnienia. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Pobiera lub ustawia nazwę linii trendu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Pobiera lub ustawia nazwę linii trendu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Pobiera lub ustawia typ linii trendu. Odczyt/zapis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Zwraca:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Pobiera lub ustawia typ linii trendu. Odczyt/zapis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje format linii trendu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje format linii trendu. Odczyt/zapis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana przed danymi serii. Na wykresach punktowych i nie-punktowych wartość może być dowolną nieujemną wartością. Odczyt/zapis double.

**Zwraca:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana przed danymi serii. Na wykresach punktowych i nie-punktowych wartość może być dowolną nieujemną wartością. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana po danych serii. Na wykresach punktowych i nie-punktowych wartość może być dowolną nie-ujemną wartością. Odczyt/zapis double.

**Zwraca:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu jest wydłużana po danych serii. Na wykresach punktowych i nie-punktowych wartość może być dowolną nie-ujemną wartością. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Określa wartość, w której linia trendu przecina oś Y. Właściwość ta jest obsługiwana wyłącznie, gdy typ linii trendu to exp, linear lub poly. Odczyt/zapis double.

**Zwraca:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Określa wartość, w której linia trendu przecina oś Y. Właściwość ta jest obsługiwana wyłącznie, gdy typ linii trendu to exp, linear lub poly. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Określa, że równanie linii trendu jest wyświetlane na wykresie (w tym samym etykiecie co wartość R-kwadrat). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Określa, że równanie linii trendu jest wyświetlane na wykresie (w tym samym etykiecie co wartość R-kwadrat). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Odczyt/zapis byte.

**Zwraca:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Określa okres linii trendu dla średniej ruchomej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być w przedziale od 2 do 255. Odczyt/zapis byte.

**Zwraca:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Określa okres linii trendu dla średniej ruchomej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być w przedziale od 2 do 255. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tym samym etykiecie co równanie). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tym samym etykiecie co równanie). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje pozycję legendy związaną z tą linią trendu. Tylko do odczytu [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst nowego TextFrameForOverriding. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Może zawierać sformatowany tekst. Jeśli ta właściwość nie jest nullem, wartość tego sformatowanego tekstu zastępuje automatycznie generowany tekst etykiety danych. Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, ShowValue, … i formatowany właściwością TextFormatManager.TextFormat. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Zwraca format tekstu. Tylko do odczytu [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Zwraca:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
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

Zwraca slajd nadrzędny formatu wypełnienia. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną formatu wypełnienia. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)