---
title: LineFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt das Format einer Linie dar.
type: docs
url: /de/com.aspose.slides/lineformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

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
| [getWidth()](#getWidth--) | Gibt die Breite einer Linie zurück oder legt sie fest. |
| [setWidth(double value)](#setWidth-double-) | Gibt die Breite einer Linie zurück oder legt sie fest. |
| [getDashStyle()](#getDashStyle--) | Gibt den Linienstrichstil zurück oder legt ihn fest. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Gibt den Linienstrichstil zurück oder legt ihn fest. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Gibt das benutzerdefinierte Strichmuster zurück oder legt es fest. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Gibt das benutzerdefinierte Strichmuster zurück oder legt es fest. |
| [getCapStyle()](#getCapStyle--) | Gibt den Linienende-Stil zurück oder legt ihn fest. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Gibt den Linienende-Stil zurück oder legt ihn fest. |
| [getStyle()](#getStyle--) | Gibt den Linienstil zurück oder legt ihn fest. |
| [setStyle(byte value)](#setStyle-byte-) | Gibt den Linienstil zurück oder legt ihn fest. |
| [getAlignment()](#getAlignment--) | Gibt die Linienausrichtung zurück oder legt sie fest. |
| [setAlignment(byte value)](#setAlignment-byte-) | Gibt die Linienausrichtung zurück oder legt sie fest. |
| [getJoinStyle()](#getJoinStyle--) | Gibt den Linienverbindungsstil zurück oder legt ihn fest. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Gibt den Linienverbindungsstil zurück oder legt ihn fest. |
| [getMiterLimit()](#getMiterLimit--) | Gibt das Schnittwinkel-Limit einer Linie zurück oder legt es fest. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Gibt das Schnittwinkel-Limit einer Linie zurück oder legt es fest. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder legt ihn fest. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder legt ihn fest. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder legt ihn fest. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder legt ihn fest. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder legt sie fest. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder legt sie fest. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder legt sie fest. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder legt sie fest. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Gibt die Pfeilspitzlänge am Anfang einer Linie zurück oder legt sie fest. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Gibt die Pfeilspitzlänge am Anfang einer Linie zurück oder legt sie fest. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Gibt die Pfeilspitzlänge am Ende einer Linie zurück oder legt sie fest. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Gibt die Pfeilspitzlänge am Ende einer Linie zurück oder legt sie fest. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bestimmt, ob die beiden LineFormat-Instanzen gleich sind. |
| [getEffective()](#getEffective--) | Ermittelt wirksame Linienformatierungsdaten mit angewandter Vererbung. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabe:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vergleicht mit dem angegebenen Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Rückgabe:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Gibt true zurück, wenn das Linienformat nicht definiert ist (wie gerade erstellt, Standard). Nur-Lese boolean .

**Rückgabe:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Gibt das Füllformat einer Linie zurück. Nur-Lese [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Rückgabe:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Gibt das Skizzenformat einer Linie zurück. Nur-Lese [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Rückgabe:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Gibt die Breite einer Linie zurück oder legt sie fest. Lesen/Schreiben  double .

**Rückgabe:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Gibt die Breite einer Linie zurück oder legt sie fest. Lesen/Schreiben  double .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Gibt den Linienstrichstil zurück oder legt ihn fest. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Rückgabe:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Gibt den Linienstrichstil zurück oder legt ihn fest. Lesen/Schreiben [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Gibt das benutzerdefinierte Strichmuster zurück oder legt es fest. Lesen/Schreiben  float[] .

**Rückgabe:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Gibt das benutzerdefinierte Strichmuster zurück oder legt es fest. Lesen/Schreiben  float[] .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Gibt den Linienende-Stil zurück oder legt ihn fest. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Rückgabe:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Gibt den Linienende-Stil zurück oder legt ihn fest. Lesen/Schreiben [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Gibt den Linienstil zurück oder legt ihn fest. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Rückgabe:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Gibt den Linienstil zurück oder legt ihn fest. Lesen/Schreiben [LineStyle](../../com.aspose.slides/linestyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Gibt die Linienausrichtung zurück oder legt sie fest. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Rückgabe:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Gibt die Linienausrichtung zurück oder legt sie fest. Lesen/Schreiben [LineAlignment](../../com.aspose.slides/linealignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Gibt den Linienverbindungsstil zurück oder legt ihn fest. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Rückgabe:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Gibt den Linienverbindungsstil zurück oder legt ihn fest. Lesen/Schreiben [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Gibt das Schnittwinkel-Limit einer Linie zurück oder legt es fest. Lesen/Schreiben  float .

**Rückgabe:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Gibt das Schnittwinkel-Limit einer Linie zurück oder legt es fest. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder legt ihn fest. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Anfang einer Linie zurück oder legt ihn fest. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder legt ihn fest. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Gibt den Pfeilspitzenstil am Ende einer Linie zurück oder legt ihn fest. Lesen/Schreiben [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Gibt die Pfeilspitzenbreite am Anfang einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Gibt die Pfeilspitzenbreite am Ende einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Gibt die Pfeilspitzlänge am Anfang einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Gibt die Pfeilspitzlänge am Anfang einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Gibt die Pfeilspitzlänge am Ende einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Gibt die Pfeilspitzlänge am Ende einer Linie zurück oder legt sie fest. Lesen/Schreiben [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Bestimmt, ob die beiden LineFormat-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Der LineFormat, mit dem der aktuelle LineFormat verglichen werden soll. |

**Rückgabe:**
boolean - **true**, wenn der angegebene LineFormat dem aktuellen LineFormat entspricht; sonst **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Ermittelt wirksame Linienformatierungsdaten mit angewandter Vererbung.

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
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Ein [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).