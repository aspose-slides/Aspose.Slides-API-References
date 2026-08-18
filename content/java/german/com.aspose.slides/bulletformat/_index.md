---
title: BulletFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt Eigenschaften für die Aufzählungsformatierung eines Absatzes dar.
type: docs
url: /de/com.aspose.slides/bulletformat/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)  
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Stellt Eigenschaften für die Aufzählungsformatierung eines Absatzes dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liefert oder setzt den Aufzählungstyp eines Absatzes ohne Vererbung. |
| [setType(byte value)](#setType-byte-) | Liefert oder setzt den Aufzählungstyp eines Absatzes ohne Vererbung. |
| [getChar()](#getChar--) | Liefert oder setzt das Aufzählungszeichen eines Absatzes ohne Vererbung. |
| [setChar(char value)](#setChar-char-) | Liefert oder setzt das Aufzählungszeichen eines Absatzes ohne Vererbung. |
| [getFont()](#getFont--) | Liefert oder setzt die Aufzählungsschriftart eines Absatzes ohne Vererbung. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Liefert oder setzt die Aufzählungsschriftart eines Absatzes ohne Vererbung. |
| [getHeight()](#getHeight--) | Liefert oder setzt die Aufzählungshöhe eines Absatzes ohne Vererbung. |
| [setHeight(float value)](#setHeight-float-) | Liefert oder setzt die Aufzählungshöhe eines Absatzes ohne Vererbung. |
| [getColor()](#getColor--) | Liefert das Farbformat einer Aufzählung eines Absatzes ohne Vererbung. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Liefert oder setzt die erste Zahl, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Liefert oder setzt die erste Zahl, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Liefert oder setzt den Stil einer nummerierten Aufzählung ohne Vererbung. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Liefert oder setzt den Stil einer nummerierten Aufzählung ohne Vererbung. |
| [isBulletHardColor()](#isBulletHardColor--) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [isBulletHardFont()](#isBulletHardFont--) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [getPicture()](#getPicture--) | Liefert das Bild, das als Aufzählung in einem Absatz ohne Vererbung verwendet wird. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Setzt standardmäßige, von Null verschiedene Verschiebungen für den effektiven Absatz-Einzug und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungen/Nummerierungen aktiviert werden). |
| [getEffective()](#getEffective--) | Liefert effektive Aufzählungsformatierungsdaten mit angewandter Vererbung. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Liefert oder setzt den Aufzählungstyp eines Absatzes ohne Vererbung. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Rückgabe:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Liefert oder setzt den Aufzählungstyp eines Absatzes ohne Vererbung. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Liefert oder setzt das Aufzählungszeichen eines Absatzes ohne Vererbung. Lesen/Schreiben char .

**Rückgabe:**  
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Liefert oder setzt das Aufzählungszeichen eines Absatzes ohne Vererbung. Lesen/Schreiben char .

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Liefert oder setzt die Aufzählungsschriftart eines Absatzes ohne Vererbung. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Liefert oder setzt die Aufzählungsschriftart eines Absatzes ohne Vererbung. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Liefert oder setzt die Aufzählungshöhe eines Absatzes ohne Vererbung. Der Wert Float.NaN bestimmt, dass die Aufzählung die Höhe vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben float .

--------------------

Ein negativer Höhenwert bedeutet, dass die Höhe in Punkten angegeben wird, und ein positiver Wert bedeutet, dass die Höhe als Prozentsatz des umgebenden Textes angegeben wird.

**Rückgabe:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Liefert oder setzt die Aufzählungshöhe eines Absatzes ohne Vererbung. Der Wert Float.NaN bestimmt, dass die Aufzählung die Höhe vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben float .

--------------------

Ein negativer Höhenwert bedeutet, dass die Höhe in Punkten angegeben wird, und ein positiver Wert bedeutet, dass die Höhe als Prozentsatz des umgebenden Textes angegeben wird.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Liefert das Farbformat einer Aufzählung eines Absatzes ohne Vererbung. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Liefert oder setzt die erste Zahl, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. Lesen/Schreiben short .

**Rückgabe:**  
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Liefert oder setzt die erste Zahl, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. Lesen/Schreiben short .

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Liefert oder setzt den Stil einer nummerierten Aufzählung ohne Vererbung. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Rückgabe:**  
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Liefert oder setzt den Stil einer nummerierten Aufzählung ohne Vererbung. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. **NullableBool.True** wenn die Aufzählung eine eigene Farbe hat und **NullableBool.False** wenn die Aufzählung die Farbe vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**  
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. **NullableBool.True** wenn die Aufzählung eine eigene Farbe hat und **NullableBool.False** wenn die Aufzählung die Farbe vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. **NullableBool.True** wenn die Aufzählung eine eigene Schriftart hat und **NullableBool.False** wenn die Aufzählung die Schriftart vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**  
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. **NullableBool.True** wenn die Aufzählung eine eigene Schriftart hat und **NullableBool.False** wenn die Aufzählung die Schriftart vom ersten Abschnitt im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Liefert das Bild, das als Aufzählung in einem Absatz ohne Vererbung verwendet wird. Nur lesbar [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Rückgabe:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Setzt standardmäßige, von Null verschiedene Verschiebungen für den effektiven Absatz-Einzug und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungen/Nummerierungen aktiviert werden). Wenn Aufzählungen deaktiviert sind, werden der Absatz-Einzug und MarginLeft lediglich zurückgesetzt (wie PowerPoint es tut, wenn Absatz-Aufzählungen/Nummerierungen deaktiviert werden). Indent-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts – angewendet. Nicht-Null-Indent-Verschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (macht Ergebniswerte zu lokalen Werten).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Liefert effektive Aufzählungsformatierungsdaten mit angewandter Vererbung.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) – ein [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbarer long.

**Rückgabe:**  
long