---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /pl/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Reprezentuje format tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt właściwości wypełnienia tabeli. |
| [getTransparency()](#getTransparency--) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |
| [setTransparency(float value)](#setTransparency-float-) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabel. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Zwraca obiekt właściwości wypełnienia tabeli. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Pobiera efektywne właściwości formatowania tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabel.

**Returns:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).