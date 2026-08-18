---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
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
| [getBorderLeft()](#getBorderLeft--) | Zwraca obiekt właściwości linii lewego obramowania. |
| [getBorderTop()](#getBorderTop--) | Zwraca obiekt właściwości linii górnego obramowania. |
| [getBorderRight()](#getBorderRight--) | Zwraca obiekt właściwości linii prawego obramowania. |
| [getBorderBottom()](#getBorderBottom--) | Zwraca obiekt właściwości linii dolnego obramowania. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Zwraca obiekt właściwości linii przekątnej od lewego-górnego do prawego-dolnego. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Zwraca obiekt właściwości linii przekątnej od lewego-dolnego do prawego-górnego. |
| [getTransparency()](#getTransparency--) | Pobiera lub ustawia przejrzystość koloru wypełnienia. |
| [setTransparency(float value)](#setTransparency-float-) | Pobiera lub ustawia przejrzystość koloru wypełnienia. |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania komórki tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli. |
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

Zwraca obiekt właściwości linii lewego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Zwraca obiekt właściwości linii górnego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Zwraca obiekt właściwości linii prawego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Zwraca obiekt właściwości linii dolnego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Zwraca obiekt właściwości linii przekątnej od lewego-górnego do prawego-dolnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Zwraca obiekt właściwości linii przekątnej od lewego-dolnego do prawego-górnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Pobiera lub ustawia przejrzystość koloru wypełnienia. odczyt/zapis  float .

**Zwraca:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Pobiera lub ustawia przejrzystość koloru wypełnienia. odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Pobiera efektywne właściwości formatowania komórki tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

**Zwraca:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).