---
title: ICellFormat
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje format komórki tabeli.
type: docs
url: /pl/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Reprezentuje format komórki tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt właściwości wypełnienia komórki. |
| [getBorderLeft()](#getBorderLeft--) | Zwraca obiekt właściwości linii lewej krawędzi. |
| [getBorderTop()](#getBorderTop--) | Zwraca obiekt właściwości linii górnej krawędzi. |
| [getBorderRight()](#getBorderRight--) | Zwraca obiekt właściwości linii prawej krawędzi. |
| [getBorderBottom()](#getBorderBottom--) | Zwraca obiekt właściwości linii dolnej krawędzi. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Zwraca obiekt właściwości linii przekątnej od lewego górnego do prawego dolnego. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Zwraca obiekt właściwości linii przekątnej od lewego dolnego do prawego górnego. |
| [getTransparency()](#getTransparency--) | Uzyskuje lub ustawia przezroczystość koloru wypełnienia. |
| [setTransparency(float value)](#setTransparency-float-) | Uzyskuje lub ustawia przezroczystość koloru wypełnienia. |
| [getEffective()](#getEffective--) | Uzyskuje skuteczne właściwości formatowania komórki tabeli z dziedziczeniem i zastosowanymi stylami tabeli. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Zwraca obiekt właściwości wypełnienia komórki. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Zwraca obiekt właściwości linii lewej krawędzi. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Zwraca obiekt właściwości linii górnej krawędzi. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Zwraca obiekt właściwości linii prawej krawędzi. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Zwraca obiekt właściwości linii dolnej krawędzi. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Zwraca obiekt właściwości linii przekątnej od lewego górnego do prawego dolnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Zwraca obiekt właściwości linii przekątnej od lewego dolnego do prawego górnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Uzyskuje lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Zwraca:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Uzyskuje lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Uzyskuje skuteczne właściwości formatowania komórki tabeli z dziedziczeniem i zastosowanymi stylami tabeli.

**Zwraca:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).