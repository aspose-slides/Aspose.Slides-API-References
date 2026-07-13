---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Zapewnia dostęp do pasków rosnących i malejących wykresu liniowego lub giełdowego.
type: docs
url: /pl/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Zapewnia dostęp do pasków rosnących i malejących wykresu liniowego lub giełdowego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Zwraca format pasków rosnących. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Zwraca format pasków malejących. |
| [hasUpDownBars()](#hasUpDownBars--) | Określa, czy wykres ma paski rosnące/malejące. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Określa, czy wykres ma paski rosnące/malejące. |
| [getGapWidth()](#getGapWidth--) | Zwraca lub ustawia szerokość przerwy. |
| [setGapWidth(int value)](#setGapWidth-int-) | Zwraca lub ustawia szerokość przerwy. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Zwraca format pasków rosnących. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Zwraca format pasków malejących. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Określa, czy wykres ma paski rosnące/malejące. Do odczytu i zapisu boolean.

**Zwraca:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Określa, czy wykres ma paski rosnące/malejące. Do odczytu i zapisu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Zwraca lub ustawia szerokość przerwy. Do odczytu i zapisu int.

**Zwraca:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Zwraca lub ustawia szerokość przerwy. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |