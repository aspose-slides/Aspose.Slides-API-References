---
title: IBulletFormat
second_title: Aspose.Slides Androidhoz – Java API-referencia
description: A bekezdés golyóformázási tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

A bekezdés golyóformázási tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Returns or sets the bullet type of a paragraph with no inheritance. |
| [setType(byte value)](#setType-byte-) | Returns or sets the bullet type of a paragraph with no inheritance. |
| [getChar()](#getChar--) | Returns or sets the bullet char of a paragraph with no inheritance. |
| [setChar(char value)](#setChar-char-) | Returns or sets the bullet char of a paragraph with no inheritance. |
| [getFont()](#getFont--) | Returns or sets the bullet font of a paragraph with no inheritance. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Returns or sets the bullet font of a paragraph with no inheritance. |
| [getHeight()](#getHeight--) | Returns or sets the bullet height of a paragraph with no inheritance. |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the bullet height of a paragraph with no inheritance. |
| [getColor()](#getColor--) | Returns the color format of a bullet of a paragraph with no inheritance. |
| [getPicture()](#getPicture--) | Returns the picture used as a bullet in a paragraph with no inheritance. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returns or sets the style of a numbered bullet with no inheritance. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returns or sets the style of a numbered bullet with no inheritance. |
| [isBulletHardColor()](#isBulletHardColor--) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [isBulletHardFont()](#isBulletHardFont--) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). |
| [getEffective()](#getEffective--) | Gets effective bullet formatting data with the inheritance applied. |
### getType() {#getType--}
```
public abstract byte getType()
```

Visszaadja vagy beállítja a bekezdés golyó típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Visszatérési érték:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Visszaadja vagy beállítja a bekezdés golyó típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Visszaadja vagy beállítja a bekezdés golyó karakterét öröklődés nélkül. Olvasás/írás char.

**Visszatérési érték:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Visszaadja vagy beállítja a bekezdés golyó karakterét öröklődés nélkül. Olvasás/írás char.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Visszaadja vagy beállítja a bekezdés golyó betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Visszaadja vagy beállítja a bekezdés golyó betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Visszaadja vagy beállítja a bekezdés golyó magasságát öröklődés nélkül. A Float.NaN érték azt jelzi, hogy a golyó a bekezdés első részéből örökli a magasságot. Olvasás/írás float.

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Visszaadja vagy beállítja a bekezdés golyó magasságát öröklődés nélkül. A Float.NaN érték azt jelzi, hogy a golyó a bekezdés első részéből örökli a magasságot. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Visszaadja a bekezdés golyó színformátumát öröklődés nélkül. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Visszaadja a bekezdés golyóként használt képet öröklődés nélkül. Csak olvasható [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Visszatérési érték:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Visszaadja vagy beállítja a számolt golyók csoportjában használt első számot öröklődés nélkül. Olvasás/írás short.

**Visszatérési érték:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Visszaadja vagy beállítja a számolt golyók csoportjában használt első számot öröklődés nélkül. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Visszaadja vagy beállítja a számozott golyó stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Visszatérési érték:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Visszaadja vagy beállítja a számozott golyó stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Meghatározza, hogy a golyó saját színnel rendelkezik-e, vagy a bekezdés első részéből örökli azt. **NullableBool#True** ha a golyó saját színnel rendelkezik, és **NullableBool#False** ha a golyó a bekezdés első részéből örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Meghatározza, hogy a golyó saját színnel rendelkezik-e, vagy a bekezdés első részéből örökli azt. **NullableBool#True** ha a golyó saját színnel rendelkezik, és **NullableBool#False** ha a golyó a bekezdés első részéből örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e, vagy a bekezdés első részéből örökli azt. **NullableBool#True** ha a golyó saját betűtípussal rendelkezik, és **NullableBool#False** ha a golyó a bekezdés első részéből örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e, vagy a bekezdés első részéből örökli azt. **NullableBool#True** ha a golyó saját betűtípussal rendelkezik, és **NullableBool#False** ha a golyó a bekezdés első részéből örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Beállítja az alapértelmezett nem nulla eltolásokat a hatékony bekezdés Behúzás és BalMargó számára, amikor a golyók engedélyezve vannak (hasonlóan a PowerPoint-hoz, ha engedélyezi a bekezdés golyókat/számozást). Ha a golyók le vannak tiltva, akkor csak visszaállítja a bekezdés Behúzást és BalMargót (mint a PowerPoint tiltás esetén). Az eltolások a jelenlegi golyó kontextusra – IBulletFormat.Type, .NumberedBulletStyle és az első rész FontHeight – vonatkoznak. A nem nulla eltolások a jelenlegi bekezdés hatékony Behúzására és BalMargójára kerülnek alkalmazásra (az eredményértékek helyi értékek lesznek).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Megkapja a hatékony golyóformázási adatokat az öröklődés alkalmazásával.

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

**Visszatérési érték:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).