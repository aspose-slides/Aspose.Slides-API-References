---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /de/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Stellt die Aufzählungsformatierungseigenschaften eines Absatzes dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest. |
| [setType(byte value)](#setType-byte-) | Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest. |
| [getChar()](#getChar--) | Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt es fest. |
| [setChar(char value)](#setChar-char-) | Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt es fest. |
| [getFont()](#getFont--) | Gibt die Aufzählungsschriftart eines Absatzes ohne Vererbung zurück oder legt sie fest. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Gibt die Aufzählungsschriftart eines Absatzes ohne Vererbung zurück oder legt sie fest. |
| [getHeight()](#getHeight--) | Gibt die Aufzählungshöhe eines Absatzes ohne Vererbung zurück oder legt sie fest. |
| [setHeight(float value)](#setHeight-float-) | Gibt die Aufzählungshöhe eines Absatzes ohne Vererbung zurück oder legt sie fest. |
| [getColor()](#getColor--) | Gibt das Farbformat einer Aufzählung eines Absatzes ohne Vererbung zurück. |
| [getPicture()](#getPicture--) | Gibt das Bild zurück, das als Aufzählung in einem Absatz ohne Vererbung verwendet wird. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Gibt den Stil einer nummerierten Aufzählung ohne Vererbung zurück oder legt ihn fest. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Gibt den Stil einer nummerierten Aufzählung ohne Vererbung zurück oder legt ihn fest. |
| [isBulletHardColor()](#isBulletHardColor--) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnittsteil im Absatz erbt. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnittsteil im Absatz erbt. |
| [isBulletHardFont()](#isBulletHardFont--) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnittsteil im Absatz erbt. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnittsteil im Absatz erbt. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Setzt Standardverschiebungen ungleich Null für den wirksamen Absatz-Einzug und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Absatzaufzählungen/Nummerierung aktiviert werden). |
| [getEffective()](#getEffective--) | Holt wirksame Aufzählungsformatierungsdaten mit angewandter Vererbung. |
### getType() {#getType--}
```
public abstract byte getType()
```

Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Rückgabe:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt es fest. Lesen/Schreiben char.

**Rückgabe:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt es fest. Lesen/Schreiben char.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Gibt die Aufzählungsschriftart eines Absatzes ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Gibt die Aufzählungsschriftart eines Absatzes ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Gibt die Aufzählungshöhe eines Absatzes ohne Vererbung zurück oder legt sie fest. Der Wert Float.NaN bestimmt, dass die Aufzählung die Höhe vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben float.

**Rückgabe:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Gibt die Aufzählungshöhe eines Absatzes ohne Vererbung zurück oder legt sie fest. Der Wert Float.NaN bestimmt, dass die Aufzählung die Höhe vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Gibt das Farbformat einer Aufzählung eines Absatzes ohne Vererbung zurück. Nur lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Gibt das Bild zurück, das als Aufzählung in einem Absatz ohne Vererbung verwendet wird. Nur lesen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Rückgabe:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. Lesen/Schreiben short.

**Rückgabe:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird. Lesen/Schreiben short.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Gibt den Stil einer nummerierten Aufzählung ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Rückgabe:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Gibt den Stil einer nummerierten Aufzählung ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnittsteil im Absatz erbt. **NullableBool\#True** wenn die Aufzählung eine eigene Farbe hat und **NullableBool\#False** wenn die Aufzählung die Farbe vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnittsteil im Absatz erbt. **NullableBool\#True** wenn die Aufzählung eine eigene Farbe hat und **NullableBool\#False** wenn die Aufzählung die Farbe vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnittsteil im Absatz erbt. **NullableBool\#True** wenn die Aufzählung eine eigene Schriftart hat und **NullableBool\#False** wenn die Aufzählung die Schriftart vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnittsteil im Absatz erbt. **NullableBool\#True** wenn die Aufzählung eine eigene Schriftart hat und **NullableBool\#False** wenn die Aufzählung die Schriftart vom ersten Abschnittsteil im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Setzt Standardverschiebungen ungleich Null für den wirksamen Absatz-Einzug und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Absatzaufzählungen/Nummerierung aktiviert werden). Wenn Aufzählungen deaktiviert sind, werden lediglich Absatz-Einzug und MarginLeft zurückgesetzt (wie PowerPoint es tut, wenn Absatzaufzählungen/Nummerierung deaktiviert werden). Die Einrückungs-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext angewendet – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnittsteils. Nicht-null-Einrückungs-Verschiebungen werden auf den wirksamen Einzug und MarginLeft des aktuellen Absatzes angewendet (machen die Ergebniswerte zu lokalen Werten).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Holt wirksame Aufzählungsformatierungsdaten mit angewandter Vererbung.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).