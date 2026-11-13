---
title: CachedChartValue
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje wartość wykresu z pamięci podręcznej, np. X, Y, rozmiar bąbelka lub wartość główną.
type: docs
url: /pl/com.aspose.slides/cachedchartvalue/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Reprezentuje wartość wykresu z pamięci podręcznej (np. X, Y, rozmiar bąbelka lub wartość główną).
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [toString()](#toString--) | Zwraca łańcuch znaków będący reprezentacją wartości z pamięci podręcznej. |
| [toDouble()](#toDouble--) | Konwertuje wartość z pamięci podręcznej na typ double. |
| [getData()](#getData--) | Pobiera obiekt danych z pamięci podręcznej. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Zwraca łańcuch znaków będący reprezentacją wartości z pamięci podręcznej.

**Zwraca:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Konwertuje wartość z pamięci podręcznej na typ double.

**Zwraca:**
double - Reprezentacja liczbowa, lub Double.NaN jeśli Data (\#getData.getData/\#setData(Object).setData(Object)) jest nullem lub nie może zostać skonwertowana na typ double.
### getData() {#getData--}
```
public final Object getData()
```


Pobiera obiekt danych z pamięci podręcznej. Tylko do odczytu Object .

**Zwraca:**
java.lang.Object