---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /pl/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Zapewnia dostęp do pasków górnych i dolnych wykresu liniowego lub giełdowego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Zwraca format pasków górnych. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Zwraca format pasków dolnych. |
| [hasUpDownBars()](#hasUpDownBars--) | Określa, czy wykres ma paski górne i dolne. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Określa, czy wykres ma paski górne i dolne. |
| [getGapWidth()](#getGapWidth--) | Zwraca lub ustawia szerokość przerwy. |
| [setGapWidth(int value)](#setGapWidth-int-) | Zwraca lub ustawia szerokość przerwy. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Zwraca format pasków górnych. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Zwraca format pasków dolnych. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Określa, czy wykres ma paski górne i dolne. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Określa, czy wykres ma paski górne i dolne. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Zwraca lub ustawia szerokość przerwy. Odczyt/zapis int.

**Zwraca:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Zwraca lub ustawia szerokość przerwy. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |