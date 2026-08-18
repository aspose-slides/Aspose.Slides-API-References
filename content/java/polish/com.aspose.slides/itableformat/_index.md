---
title: ITableFormat
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje format tabeli.
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
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania tabeli z zastosowanym dziedziczeniem i stylami tabel. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Zwraca obiekt właściwości wypełnienia tabeli. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Zwraca:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Pobiera efektywne właściwości formatowania tabeli z zastosowanym dziedziczeniem i stylami tabel.

**Zwraca:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).