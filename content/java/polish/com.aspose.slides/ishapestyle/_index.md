---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje odwołanie do stylu kształtu.
type: docs
url: /pl/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Reprezentuje odwołanie do stylu kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLineColor()](#getLineColor--) | Returns a shape's outline color. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Returns or sets line's column index in a style matrix. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Returns or sets line's column index in a style matrix. |
| [getFillColor()](#getFillColor--) | Returns a shape's fill color. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Returns or sets shape's fill column index in style matrices. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Returns or sets shape's fill column index in style matrices. |
| [getEffectColor()](#getEffectColor--) | Returns a shape's effect color. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Returns or sets shape's effect column index in a style matrix. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Returns or sets shape's effect column index in a style matrix. |
| [getFontColor()](#getFontColor--) | Returns a shape's font color. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Returns or sets shape's font index in a font collection. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Returns or sets shape's font index in a font collection. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Zwraca kolor obrysu kształtu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Zwraca lub ustawia indeks kolumny linii w macierzy stylu. Do odczytu i zapisu int.

**Zwraca:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Zwraca lub ustawia indeks kolumny linii w macierzy stylu. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Zwraca kolor wypełnienia kształtu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. 0 oznacza brak wypełnienia, dodatnia wartość – indeks w stylach wypełnienia motywu, ujemna wartość – indeks w stylach tła motywu. Do odczytu i zapisu short.

**Zwraca:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. 0 oznacza brak wypełnienia, dodatnia wartość – indeks w stylach wypełnienia motywu, ujemna wartość – indeks w stylach tła motywu. Do odczytu i zapisu short.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Zwraca kolor efektu kształtu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. Do odczytu i zapisu long.

**Zwraca:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. Do odczytu i zapisu long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Zwraca kolor czcionki kształtu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. Do odczytu i zapisu [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Zwraca:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. Do odczytu i zapisu [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |