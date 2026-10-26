---
title: LineFormat
second_title: Aspose.Slides für Android – Java API-Referenz
description: Stellt das Format einer Linie dar.
type: docs
url: /de/com.aspose.slides/lineformat/
---
**Vererbung:** java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Stellt das Format einer Linie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
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
| [getMiterLimit()](#getMiterLimit--) | Gibt die Begrenzung des Gehrungswinkels einer Linie zurück oder setzt sie. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Gibt die Begrenzung des Gehrungswinkels einer Linie zurück oder setzt sie. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Gibt die Breite der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Gibt die Breite der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Gibt die Breite der Pfeilspitze am Ende einer Linie zurück oder setzt sie. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Gibt die Breite der Pfeilspitze am Ende einer Linie zurück oder setzt sie. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Gibt die Länge der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Gibt die Länge der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Gibt die Länge der Pfeilspitze am Ende einer Linie zurück oder setzt sie. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Gibt die Länge der Pfeilspitze am Ende einer Linie zurück oder setzt sie. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bestimmt, ob die beiden LineFormat-Instanzen gleich sind. |
| [getEffective()](#getEffective--) | Ermittelt effektive Linienstil-Daten mit angewandter Vererbung. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vergleicht mit dem angegebenen Objekt.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| obj | java.lang.Object |  |

**Rückgabe:**  
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Gibt true zurück, wenn das Linienformat nicht definiert ist (wie gerade erstellt, Standard). Nur lesbar boolean.

**Rückgabe:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Gibt das Füllformat einer Linie zurück. Nur lesbar [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Rückgabe:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Gibt das Skizzenformat einer Linie zurück. Nur lesbar [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Rückgabe:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Gibt die Breite einer Linie zurück oder setzt sie. Lesen/Schreiben double.

**Rückgabe:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Gibt die Breite einer Linie zurück oder setzt sie. Lesen/Schreiben double.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Gibt den Strichstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Rückgabe:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Gibt den Strichstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. Lesen/Schreiben float[] .

**Rückgabe:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Gibt das benutzerdefinierte Strichmuster zurück oder setzt es. Lesen/Schreiben float[] .

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Gibt den Endkappenstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Rückgabe:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Gibt den Endkappenstil der Linie zurück oder setzt ihn. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Gibt den Linienstil zurück oder setzt ihn. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Rückgabe:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Gibt den Linienstil zurück oder setzt ihn. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Gibt die Ausrichtung der Linie zurück oder setzt sie. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Rückgabe:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Gibt die Ausrichtung der Linie zurück oder setzt sie. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Gibt den Verbindungsstil der Linien zurück oder setzt ihn. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Rückgabe:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Gibt den Verbindungsstil der Linien zurück oder setzt ihn. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Gibt die Begrenzung des Gehrungswinkels einer Linie zurück oder setzt sie. Lesen/Schreiben float .

**Rückgabe:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Gibt die Begrenzung des Gehrungswinkels einer Linie zurück oder setzt sie. Lesen/Schreiben float .

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder setzt ihn. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Gibt die Breite der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Gibt die Breite der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Gibt die Breite der Pfeilspitze am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Gibt die Breite der Pfeilspitze am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Gibt die Länge der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Gibt die Länge der Pfeilspitze am Anfang einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Gibt die Länge der Pfeilspitze am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Gibt die Länge der Pfeilspitze am Ende einer Linie zurück oder setzt sie. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Bestimmt, ob die beiden LineFormat-Instanzen gleich sind.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Das LineFormat, das mit dem aktuellen LineFormat verglichen werden soll. |

**Rückgabe:**  
boolean – **true** wenn das angegebene LineFormat dem aktuellen LineFormat entspricht; andernfalls **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Ermittelt effektive Linienstil-Daten mit angewandter Vererbung.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).