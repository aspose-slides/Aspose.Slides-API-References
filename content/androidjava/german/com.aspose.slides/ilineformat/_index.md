---
title: ILineFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt das Format einer Linie dar.
type: docs
url: /de/com.aspose.slides/ilineformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Stellt das Format einer Linie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Gibt true zurück, wenn das Linienformat nicht definiert ist (wie gerade erstellt, Standard). |
| [getFillFormat()](#getFillFormat--) | Gibt das Füllformat einer Linie zurück. |
| [getSketchFormat()](#getSketchFormat--) | Gibt das Skizzenformat einer Linie zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite einer Linie zurück oder setzt sie. |
| [setWidth(double value)](#setWidth-double-) | Gibt die Breite einer Linie zurück oder setzt sie. |
| [getDashStyle()](#getDashStyle--) | Gibt den Strichstil der Linie zurück oder setzt ihn. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Gibt den Strichstil der Linie zurück oder setzt ihn. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. |
| [getCapStyle()](#getCapStyle--) | Gibt den Endkappenstil der Linie zurück oder setzt ihn. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Gibt den Endkappenstil der Linie zurück oder setzt ihn. |
| [getStyle()](#getStyle--) | Gibt den Linienstil zurück oder setzt ihn. |
| [setStyle(byte value)](#setStyle-byte-) | Gibt den Linienstil zurück oder setzt ihn. |
| [getAlignment()](#getAlignment--) | Gibt die Ausrichtung der Linie zurück oder setzt sie. |
| [setAlignment(byte value)](#setAlignment-byte-) | Gibt die Ausrichtung der Linie zurück oder setzt sie. |
| [getJoinStyle()](#getJoinStyle--) | Gibt den Verbindungsstil der Linien zurück oder setzt ihn. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Gibt den Verbindungsstil der Linien zurück oder setzt ihn. |
| [getMiterLimit()](#getMiterLimit--) | Gibt den Miter-Limit einer Linie zurück oder setzt ihn. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Gibt den Miter-Limit einer Linie zurück oder setzt ihn. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder setzt sie. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder setzt sie. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder setzt sie. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder setzt sie. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Gibt die Pfeilspitzenlänge am Anfang einer Linie zurück oder setzt sie. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Gibt die Pfeilspitzenlänge am Anfang einer Linie zurück oder setzt sie. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Gibt die Pfeilspitzenlänge am Ende einer Linie zurück oder setzt sie. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Gibt die Pfeilspitzenlänge am Ende einer Linie zurück oder setzt sie. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bestimmt, ob die beiden LineFormat-Instanzen gleich sind. |
| [getEffective()](#getEffective--) | Ruft die wirksamen Linienformatdaten ab, bei denen die Vererbung angewendet wurde. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Gibt true zurück, wenn das Linienformat nicht definiert ist (wie gerade erstellt, Standard). Nur lesbarer boolescher Wert.

**Rückgabe:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Gibt das Füllformat einer Linie zurück. Nur lesbar [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Rückgabe:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Gibt das Skizzenformat einer Linie zurück. Nur lesbar [ISketchFormat](../../com.aspose.slides/isketchformat).

**Rückgabe:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Gibt die Breite einer Linie zurück oder setzt sie. Lesen/Schreiben double.

**Rückgabe:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Gibt die Breite einer Linie zurück oder setzt sie. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Gibt den Strichstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Rückgabe:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Gibt den Strichstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. Lesen/Schreiben float[].

**Rückgabe:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Gibt den Endkappenstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Rückgabe:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Gibt den Endkappenstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Gibt den Linienstil zurück oder setzt ihn. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Rückgabe:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Gibt den Linienstil zurück oder setzt ihn. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Gibt die Ausrichtung der Linie zurück oder setzt sie. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Rückgabe:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Gibt die Ausrichtung der Linie zurück oder setzt sie. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Gibt den Verbindungsstil der Linien zurück oder setzt ihn. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Rückgabe:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Gibt den Verbindungsstil der Linien zurück oder setzt ihn. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Gibt den Miter-Limit einer Linie zurück oder setzt ihn. Lesen/Schreiben float.

**Rückgabe:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Gibt den Miter-Limit einer Linie zurück oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Gibt die Pfeilspitzenlänge am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Gibt die Pfeilspitzenlänge am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Gibt die Pfeilspitzenlänge am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Gibt die Pfeilspitzenlänge am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Bestimmt, ob die beiden LineFormat-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Das LineFormat, mit dem das aktuelle LineFormat verglichen wird. |

**Rückgabe:**
boolean - **true** wenn das angegebene LineFormat dem aktuellen LineFormat entspricht; andernfalls **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Ruft die wirksamen Linienformatdaten ab, bei denen die Vererbung angewendet wurde.

**Rückgabe:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Ein [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).