---
title: ILineFormatEffectiveData
second_title: Aspose.Slides dla Java – dokumentacja API
description: Niezmienny obiekt zawierający skuteczne właściwości formatowania linii.
type: docs
url: /pl/com.aspose.slides/ilineformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Niezmienny obiekt zawierający skuteczne właściwości formatowania linii.

--------------------

Ten interfejs jest używany razem z interfejsem [ILineFormat](../../com.aspose.slides/ilineformat), aby zwrócić skuteczne wartości formatowania z uwzględnieniem dziedziczenia zastosowanego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Zwraca format wypełnienia linii. |
| [getSketchFormat()](#getSketchFormat--) | Zwraca format szkicu linii. |
| [getWidth()](#getWidth--) | Zwraca szerokość linii. |
| [getDashStyle()](#getDashStyle--) | Zwraca styl kreski linii. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Zwraca niestandardowy wzorzec kreski. |
| [getCapStyle()](#getCapStyle--) | Zwraca styl zakończenia linii. |
| [getStyle()](#getStyle--) | Zwraca styl linii. |
| [getAlignment()](#getAlignment--) | Zwraca wyrównanie linii. |
| [getJoinStyle()](#getJoinStyle--) | Zwraca styl łączenia linii. |
| [getMiterLimit()](#getMiterLimit--) | Zwraca limit ścięcia linii. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Zwraca styl grotu strzałki na początku linii. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Zwraca styl grotu strzałki na końcu linii. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Zwraca szerokość grotu strzałki na początku linii. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Zwraca szerokość grotu strzałki na końcu linii. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Zwraca długość grotu strzałki na początku linii. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Zwraca długość grotu strzałki na końcu linii. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Określa, czy dwa obiekty ILineFormatEffectiveData są równe. |
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

Zwraca styl grotu strzałki na początku linii. Tylko do odczytu [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Zwraca styl grotu strzałki na końcu linii. Tylko do odczytu [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Zwraca szerokość grotu strzałki na początku linii. Tylko do odczytu [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Zwraca szerokość grotu strzałki na końcu linii. Tylko do odczytu [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Zwraca długość grotu strzałki na początku linii. Tylko do odczytu [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Zwraca długość grotu strzałki na końcu linii. Tylko do odczytu [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

Określa, czy dwa obiekty ILineFormatEffectiveData są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData, z którym porównywany jest bieżący ILineFormatEffectiveData. |

**Zwraca:**
boolean - **true** jeśli podany ILineFormatEffectiveData jest równy bieżącemu ILineFormatEffectiveData; w przeciwnym razie, **false**.