---
title: BulletFormat
second_title: Aspose.Slides for Android Java API hivatkozás
description: A bekezdés bullet formázási tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/bulletformat/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

A bekezdés bullet formázási tulajdonságait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja vagy beállítja a bekezdés bullet típusát öröklődés nélkül. |
| [setType(byte value)](#setType-byte-) | Visszaadja vagy beállítja a bekezdés bullet típusát öröklődés nélkül. |
| [getChar()](#getChar--) | Visszaadja vagy beállítja a bekezdés bullet karakterét öröklődés nélkül. |
| [setChar(char value)](#setChar-char-) | Visszaadja vagy beállítja a bekezdés bullet karakterét öröklődés nélkül. |
| [getFont()](#getFont--) | Visszaadja vagy beállítja a bekezdés bullet betűtípusát öröklődés nélkül. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a bekezdés bullet betűtípusát öröklődés nélkül. |
| [getHeight()](#getHeight--) | Visszaadja vagy beállítja a bekezdés bullet magasságát öröklődés nélkül. |
| [setHeight(float value)](#setHeight-float-) | Visszaadja vagy beállítja a bekezdés bullet magasságát öröklődés nélkül. |
| [getColor()](#getColor--) | Visszaadja a bekezdés bullet színformátumát öröklődés nélkül. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Visszaadja vagy beállítja az első számot, amely a számozott bullet csoporthoz használatos öröklődés nélkül. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Visszaadja vagy beállítja az első számot, amely a számozott bullet csoporthoz használatos öröklődés nélkül. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Visszaadja vagy beállítja egy számozott bullet stílusát öröklődés nélkül. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Visszaadja vagy beállítja egy számozott bullet stílusát öröklődés nélkül. |
| [isBulletHardColor()](#isBulletHardColor--) | Meghatározza, hogy a bullet saját színnel rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Meghatározza, hogy a bullet saját színnel rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. |
| [isBulletHardFont()](#isBulletHardFont--) | Meghatározza, hogy a bullet saját betűtípussal rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Meghatározza, hogy a bullet saját betűtípussal rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. |
| [getPicture()](#getPicture--) | Visszaadja a bekezdésben bulletként használt képet öröklődés nélkül. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft számára, amikor a bullet engedélyezett (ahogyan a PowerPoint is teszi, ha engedélyezik a bekezdés bullet/ számozást benne). |
| [getEffective()](#getEffective--) | Lekéri a hatékony bullet formázási adatokat az alkalmazott öröklődéssel. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Visszaadja vagy beállítja a bekezdés bullet típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Visszatérési érték:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Visszaadja vagy beállítja a bekezdés bullet típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

Visszaadja vagy beállítja a bekezdés bullet karakterét öröklődés nélkül. Olvasás/írás  char .

**Visszatérési érték:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Visszaadja vagy beállítja a bekezdés bullet karakterét öröklődés nélkül. Olvasás/írás  char .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

Visszaadja vagy beállítja a bekezdés bullet betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Visszaadja vagy beállítja a bekezdés bullet betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Visszaadja vagy beállítja a bekezdés bullet magasságát öröklődés nélkül. A Float.NaN érték határozza meg, hogy a bullet a bekezdés első szakaszából örökli a magasságot. Olvasás/írás  float .

--------------------

A negatív magasság érték azt jelenti, hogy a magasság pontban van megadva, és a pozitív érték azt jelenti, hogy a magasság a környező szöveg százalékában van.

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Visszaadja vagy beállítja a bekezdés bullet magasságát öröklődés nélkül. A Float.NaN érték határozza meg, hogy a bullet a bekezdés első szakaszából örökli a magasságot. Olvasás/írás  float .

--------------------

A negatív magasság érték azt jelenti, hogy a magasság pontban van megadva, és a pozitív érték azt jelenti, hogy a magasság a környező szöveg százalékában van.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Visszaadja a bekezdés bullet színformátumát öröklődés nélkül. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Visszaadja vagy beállítja az első számot, amely a számozott bullet csoporthoz használatos öröklődés nélkül. Olvasás/írás  short .

**Visszatérési érték:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Visszaadja vagy beállítja az első számot, amely a számozott bullet csoporthoz használatos öröklődés nélkül. Olvasás/írás  short .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Visszaadja vagy beállítja egy számozott bullet stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Visszatérési érték:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Visszaadja vagy beállítja egy számozott bullet stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Meghatározza, hogy a bullet saját színnel rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. **NullableBool.True** ha a bullet saját színnel rendelkezik és **NullableBool.False** ha a bullet az első szakaszból örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Meghatározza, hogy a bullet saját színnel rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. **NullableBool.True** ha a bullet saját színnel rendelkezik és **NullableBool.False** ha a bullet az első szakaszból örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Meghatározza, hogy a bullet saját betűtípussal rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. **NullableBool.True** ha a bullet saját betűtípussal rendelkezik és **NullableBool.False** ha a bullet az első szakaszból örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Meghatározza, hogy a bullet saját betűtípussal rendelkezik-e, vagy a bekezdés első szakaszából örökli azt. **NullableBool.True** ha a bullet saját betűtípussal rendelkezik és **NullableBool.False** ha a bullet az első szakaszból örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Visszaadja a bekezdésben bulletként használt képet öröklődés nélkül. Csak olvasható [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Visszatérési érték:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft számára, amikor a bullet engedélyezett (ahogyan a PowerPoint is teszi, ha engedélyezik a bekezdés bullet/ számozást benne). Ha a bullet le van tiltva, akkor csak visszaállítja a bekezdés Indent és MarginLeft értékét (ahogyan a PowerPoint is teszi, ha letiltja a bekezdés bullet/ számozást benne). Az eltolások a jelenlegi bullet kontextus tekintetében – IBulletFormat.Type, .NumberedBulletStyle és a első szakasz FontHeight – kerülnek alkalmazásra. A nem nulla eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékére vonatkoznak (az eredmény értékek lokális értékekké válnak).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Lekéri a hatékony bullet formázási adatokat az öröklődés alkalmazásával.

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
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long