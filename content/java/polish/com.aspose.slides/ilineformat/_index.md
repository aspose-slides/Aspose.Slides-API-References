---
title: ILineFormat
second_title: Aspose.Slides for Java – Dokumentacja API
description: Reprezentuje format linii.
type: docs
url: /pl/com.aspose.slides/ilineformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Reprezentuje format linii.
## Metody

| Metoda | Opis |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Zwraca true, jeśli format linii nie jest zdefiniowany (tak jak przy nowo utworzonym, domyślnym). |
| [getFillFormat()](#getFillFormat--) | Zwraca format wypełnienia linii. |
| [getSketchFormat()](#getSketchFormat--) | Zwraca format szkicu linii. |
| [getWidth()](#getWidth--) | Zwraca lub ustawia szerokość linii. |
| [setWidth(double value)](#setWidth-double-) | Zwraca lub ustawia szerokość linii. |
| [getDashStyle()](#getDashStyle--) | Zwraca lub ustawia styl kreski linii. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Zwraca lub ustawia styl kreski linii. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Zwraca lub ustawia niestandardowy wzorzec kreski. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Zwraca lub ustawia niestandardowy wzorzec kreski. |
| [getCapStyle()](#getCapStyle--) | Zwraca lub ustawia styl zakończenia linii. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Zwraca lub ustawia styl zakończenia linii. |
| [getStyle()](#getStyle--) | Zwraca lub ustawia styl linii. |
| [setStyle(byte value)](#setStyle-byte-) | Zwraca lub ustawia styl linii. |
| [getAlignment()](#getAlignment--) | Zwraca lub ustawia wyrównanie linii. |
| [setAlignment(byte value)](#setAlignment-byte-) | Zwraca lub ustawia wyrównanie linii. |
| [getJoinStyle()](#getJoinStyle--) | Zwraca lub ustawia styl łączenia linii. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Zwraca lub ustawia styl łączenia linii. |
| [getMiterLimit()](#getMiterLimit--) | Zwraca lub ustawia limit pochylenia (miter) linii. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Zwraca lub ustawia limit pochylenia (miter) linii. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Zwraca lub ustawia styl grotu strzały na początku linii. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Zwraca lub ustawia styl grotu strzały na początku linii. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Zwraca lub ustawia styl grotu strzały na końcu linii. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Zwraca lub ustawia styl grotu strzały na końcu linii. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Zwraca lub ustawia szerokość grotu strzały na początku linii. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Zwraca lub ustawia szerokość grotu strzały na początku linii. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Zwraca lub ustawia szerokość grotu strzały na końcu linii. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Zwraca lub ustawia szerokość grotu strzały na końcu linii. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Zwraca lub ustawia długość grotu strzały na początku linii. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Zwraca lub ustawia długość grotu strzały na początku linii. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Zwraca lub ustawia długość grotu strzały na końcu linii. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Zwraca lub ustawia długość grotu strzały na końcu linii. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Określa, czy dwa obiekty LineFormat są równe. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania linii z zastosowanym dziedziczeniem. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Zwraca true, jeśli format linii nie jest zdefiniowany (tak jak przy nowo utworzonym, domyślnym). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Zwraca format wypełnienia linii. Tylko do odczytu [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Zwraca:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Zwraca format szkicu linii. Tylko do odczytu [ISketchFormat](../../com.aspose.slides/isketchformat).

**Zwraca:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Zwraca lub ustawia szerokość linii. Odczyt i zapis double.

**Zwraca:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Zwraca lub ustawia szerokość linii. Odczyt i zapis double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Zwraca lub ustawia styl kreski linii. Odczyt i zapis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Zwraca:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Zwraca lub ustawia styl kreski linii. Odczyt i zapis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Zwraca lub ustawia niestandardowy wzorzec kreski. Odczyt i zapis float[].

**Zwraca:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Zwraca lub ustawia niestandardowy wzorzec kreski. Odczyt i zapis float[].

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Zwraca lub ustawia styl zakończenia linii. Odczyt i zapis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Zwraca:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Zwraca lub ustawia styl zakończenia linii. Odczyt i zapis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Zwraca lub ustawia styl linii. Odczyt i zapis [LineStyle](../../com.aspose.slides/linestyle).

**Zwraca:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Zwraca lub ustawia styl linii. Odczyt i zapis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Zwraca lub ustawia wyrównanie linii. Odczyt i zapis [LineAlignment](../../com.aspose.slides/linealignment).

**Zwraca:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Zwraca lub ustawia wyrównanie linii. Odczyt i zapis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Zwraca lub ustawia styl łączenia linii. Odczyt i zapis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Zwraca:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Zwraca lub ustawia styl łączenia linii. Odczyt i zapis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Zwraca lub ustawia limit pochylenia (miter) linii. Odczyt i zapis float.

**Zwraca:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Zwraca lub ustawia limit pochylenia (miter) linii. Odczyt i zapis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Zwraca lub ustawia styl grotu strzały na początku linii. Odczyt i zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Zwraca lub ustawia styl grotu strzały na początku linii. Odczyt i zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Zwraca lub ustawia styl grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Zwraca lub ustawia styl grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Zwraca lub ustawia szerokość grotu strzały na początku linii. Odczyt i zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Zwraca lub ustawia szerokość grotu strzały na początku linii. Odczyt i zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Zwraca lub ustawia szerokość grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Zwraca lub ustawia szerokość grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Zwraca lub ustawia długość grotu strzały na początku linii. Odczyt i zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Zwraca lub ustawia długość grotu strzały na początku linii. Odczyt i zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Zwraca lub ustawia długość grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Zwraca lub ustawia długość grotu strzały na końcu linii. Odczyt i zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Określa, czy dwa obiekty LineFormat są równe.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Obiekt LineFormat, z którym porównywany jest bieżący LineFormat. |

**Zwraca:**
boolean - **true** jeśli określony LineFormat jest równy bieżącemu LineFormat; w przeciwnym razie **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania linii z zastosowanym dziedziczeniem.

**Zwraca:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).