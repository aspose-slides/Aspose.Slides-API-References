---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: Represents marker of a chert.
type: docs
url: /pl/com.aspose.slides/imarker/
---```
public interface IMarker
```

Reprezentuje znacznik wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSymbol()](#getSymbol--) | Reprezentuje styl znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. |
| [setSymbol(int value)](#setSymbol-int-) | Reprezentuje styl znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. |
| [getFormat()](#getFormat--) | Pobiera wypełnienie znacznika. |
| [getSize()](#getSize--) | Reprezentuje rozmiar znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. |
| [setSize(int value)](#setSize-int-) | Reprezentuje rozmiar znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

Reprezentuje styl znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. Odczyt/zapis [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Zwraca:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

Reprezentuje styl znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. Odczyt/zapis [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Pobiera wypełnienie znacznika. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

Reprezentuje rozmiar znacznika w wykresie liniowym, wykresie punktowym lub wykresie radarowym. Odczyt/zapis int.

**Zwraca:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

Reprezentuje rozmiar znacznika w wykrysie liniowym, wykresie punktowym lub wykresie radarowym. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |