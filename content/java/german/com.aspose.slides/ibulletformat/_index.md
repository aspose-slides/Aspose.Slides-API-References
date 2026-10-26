---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Stellt die Aufzählungsformatierungseigenschaften eines Absatzes dar.
type: docs
url: /de/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Stellt die Aufzählungsformatierungseigenschaften eines Absatzes dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den bullet type eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [setType(byte value)](#setType-byte-) | Gibt den bullet type eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [getChar()](#getChar--) | Gibt den bullet char eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [setChar(char value)](#setChar-char-) | Gibt den bullet char eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [getFont()](#getFont--) | Gibt den bullet font eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Gibt den bullet font eines Absatzes ohne Vererbung zurück oder setzt ihn. |
| [getHeight()](#getHeight--) | Gibt die bullet height eines Absatzes ohne Vererbung zurück oder setzt sie. |
| [setHeight(float value)](#setHeight-float-) | Gibt die bullet height eines Absatzes ohne Vererbung zurück oder setzt sie. |
| [getColor()](#getColor--) | Gibt das color format eines bullet eines Absatzes ohne Vererbung zurück. |
| [getPicture()](#getPicture--) | Gibt das picture zurück, das als bullet in einem Absatz ohne Vererbung verwendet wird. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter bullets ohne Vererbung verwendet wird. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter bullets ohne Vererbung verwendet wird. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Gibt den style eines numbered bullet ohne Vererbung zurück oder setzt ihn. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Gibt den style eines numbered bullet ohne Vererbung zurück oder setzt ihn. |
| [isBulletHardColor()](#isBulletHardColor--) | Bestimmt, ob das bullet eine eigene Farbe hat oder sie von der ersten Portion im Absatz erbt. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bestimmt, ob das bullet eine eigene Farbe hat oder sie von der ersten Portion im Absatz erbt. |
| [isBulletHardFont()](#isBulletHardFont--) | Bestimmt, ob das bullet eine eigene Schrift hat oder sie von der ersten Portion im Absatz erbt. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bestimmt, ob das bullet eine eigene Schrift hat oder sie von der ersten Portion im Absatz erbt. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Setzt standardmäßige von Null verschiedene Verschiebungen für den effektiven Absatz-Indent und MarginLeft, wenn bullets aktiviert sind (wie PowerPoint es macht, wenn Absatz-Bullets/Nummerierung aktiviert werden). |
| [getEffective()](#getEffective--) | Ruft wirksame bullet-Formatierungsdaten mit angewandter Vererbung ab. |
### getType() {#getType--}
```
public abstract byte getType()
```

Gibt den bullet type eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Rückgabe:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Gibt den bullet type eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Gibt den bullet char eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben char.

**Rückgabe:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Gibt den bullet char eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben char.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Gibt den bullet font eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Gibt den bullet font eines Absatzes ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Gibt die bullet height eines Absatzes ohne Vererbung zurück oder setzt sie. Der Wert Float.NaN legt fest, dass das bullet die Höhe von der ersten Portion im Absatz erbt. Lesen/Schreiben float.

**Rückgabe:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Gibt die bullet height eines Absatzes ohne Vererbung zurück oder setzt sie. Der Wert Float.NaN legt fest, dass das bullet die Höhe von der ersten Portion im Absatz erbt. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Gibt das color format eines bullet eines Absatzes ohne Vererbung zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Gibt das picture zurück, das als bullet in einem Absatz ohne Vererbung verwendet wird. Nur lesbar [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Rückgabe:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter bullets ohne Vererbung verwendet wird. Lesen/Schreiben short.

**Rückgabe:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter bullets ohne Vererbung verwendet wird. Lesen/Schreiben short.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Gibt den style eines numbered bullet ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Rückgabe:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Gibt den style eines numbered bullet ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Bestimmt, ob das bullet eine eigene Farbe hat oder sie von der ersten Portion im Absatz erbt. **NullableBool#True** wenn das bullet eine eigene Farbe hat und **NullableBool#False** wenn das bullet die Farbe von der ersten Portion im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Bestimmt, ob das bullet eine eigene Farbe hat oder sie von der ersten Portion im Absatz erbt. **NullableBool#True** wenn das bullet eine eigene Farbe hat und **NullableBool#False** wenn das bullet die Farbe von der ersten Portion im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Bestimmt, ob das bullet eine eigene Schrift hat oder sie von der ersten Portion im Absatz erbt. **NullableBool#True** wenn das bullet eine eigene Schrift hat und **NullableBool#False** wenn das bullet die Schrift von der ersten Portion im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Bestimmt, ob das bullet eine eigene Schrift hat oder sie von der ersten Portion im Absatz erbt. **NullableBool#True** wenn das bullet eine eigene Schrift hat und **NullableBool#False** wenn das bullet die Schrift von der ersten Portion im Absatz erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Setzt standardmäßige von Null verschiedene Verschiebungen für den effektiven Absatz-Indent und MarginLeft, wenn bullets aktiviert sind (wie PowerPoint es macht, wenn Absatz-Bullets/Nummerierung aktiviert werden). Wenn bullets deaktiviert sind, werden einfach Absatz-Indent und MarginLeft zurückgesetzt (wie PowerPoint es macht, wenn Absatz-Bullets/Nummerierung deaktiviert werden). Einzugsverschiebungen werden in Bezug auf den aktuellen bullet-Kontext angewendet – IBulletFormat.Type, .NumberedBulletStyle und FontHeight der ersten Portion. Von Null verschiedene Einzugsverschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (damit Ergebniswerte lokale Werte werden).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Ruft wirksame bullet-Formatierungsdaten mit angewandter Vererbung ab.

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