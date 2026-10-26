---
title: ILineFormatEffectiveData
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Niezmienny obiekt zawierający skuteczne właściwości formatowania linii.
type: docs
url: /pl/com.aspose.slides/ilineformateffectivedata/
---
**Wszystkie implementowane interfejsy:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Niezmienny obiekt zawierający skuteczne właściwości formatowania linii.

--------------------

Ten interfejs jest używany razem z interfejsem [ILineFormat](../../com.aspose.slides/ilineformat), aby zwrócić skuteczne wartości formatowania z zastosowaniem dziedziczenia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns the line cap style. |
| [getStyle()](#getStyle--) | Returns the line style. |
| [getAlignment()](#getAlignment--) | Returns the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns the arrowhead length at the end of a line. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determines whether the two ILineFormatEffectiveData instances are equal. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Zwraca format wypełnienia linii. Tylko do odczytu [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Zwraca:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Zwraca format szkicu linii. Tylko do odczytu [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Zwraca:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Zwraca szerokość linii. Tylko do odczytu double.

**Zwraca:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Zwraca styl kreski linii. Tylko do odczytu [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Zwraca:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Zwraca niestandardowy wzorzec kreski. Tylko do odczytu float[].

**Zwraca:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Zwraca styl zakończenia linii. Tylko do odczytu [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Zwraca:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Zwraca styl linii. Tylko do odczytu [LineStyle](../../com.aspose.slides/linestyle).

**Zwraca:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Zwraca wyrównanie linii. Tylko do odczytu [LineAlignment](../../com.aspose.slides/linealignment).

**Zwraca:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Zwraca styl łączenia linii. Tylko do odczytu [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Zwraca:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Zwraca limit ścięcia linii. Tylko do odczytu float.

**Zwraca:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Zwraca styl grotu na początku linii. Tylko do odczytu [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Zwraca styl grotu na końcu linii. Tylko do odczytu [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Zwraca szerokość grotu na początku linii. Tylko do odczytu [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Zwraca szerokość grotu na końcu linii. Tylko do odczytu [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Zwraca długość grotu na początku linii. Tylko do odczytu [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Zwraca długość grotu na końcu linii. Tylko do odczytu [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Determines whether the two ILineFormatEffectiveData instances are equal.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | The ILineFormatEffectiveData to compare with the current ILineFormatEffectiveData. |

**Zwraca:**
boolean - **true**, jeśli podany ILineFormatEffectiveData jest równy bieżącemu ILineFormatEffectiveData; w przeciwnym razie **false**.