---
title: IShapeStyle
second_title: Aspose.Slides dla Androida – odniesienie do Java API
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
| [getLineColor()](#getLineColor--) | Zwraca kolor konturu kształtu. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Zwraca lub ustawia indeks kolumny linii w macierzy stylu. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Zwraca lub ustawia indeks kolumny linii w macierzy stylu. |
| [getFillColor()](#getFillColor--) | Zwraca kolor wypełnienia kształtu. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. |
| [getEffectColor()](#getEffectColor--) | Zwraca kolor efektu kształtu. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. |
| [getFontColor()](#getFontColor--) | Zwraca kolor czcionki kształtu. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Zwraca kolor konturu kształtu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Zwraca lub ustawia indeks kolumny linii w macierzy stylu. Odczyt/zapis int.

**Zwraca:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Zwraca lub ustawia indeks kolumny linii w macierzy stylu. Odczyt/zapis int.

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

Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. 0 oznacza brak wypełnienia, dodatnia wartość – indeks w stylach wypełnienia motywu, ujemna wartość – indeks w stylach tła motywu. Odczyt/zapis short.

**Zwraca:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Zwraca lub ustawia indeks kolumny wypełnienia kształtu w macierzach stylu. 0 oznacza brak wypełnienia, dodatnia wartość – indeks w stylach wypełnienia motywu, ujemna wartość – indeks w stylach tła motywu. Odczyt/zapis short.

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

Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. Odczyt/zapis long.

**Zwraca:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Zwraca lub ustawia indeks kolumny efektu kształtu w macierzy stylu. Odczyt/zapis long.

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

Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. Odczyt/zapis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Zwraca:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Zwraca lub ustawia indeks czcionki kształtu w kolekcji czcionek. Odczyt/zapis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |