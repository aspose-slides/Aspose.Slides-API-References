---
title: IBulletFormat
second_title: Aspose.Slides for Java API-referencia
description: A bekezdés jelölő formázási tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

A bekezdés jelölő formázási tulajdonságait reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja vagy beállítja a bekezdés jelölő típusát öröklődés nélkül. |
| [setType(byte value)](#setType-byte-) | Visszaadja vagy beállítja a bekezdés jelölő típusát öröklődés nélkül. |
| [getChar()](#getChar--) | Visszaadja vagy beállítja a bekezdés jelölő karakterét öröklődés nélkül. |
| [setChar(char value)](#setChar-char-) | Visszaadja vagy beállítja a bekezdés jelölő karakterét öröklődés nélkül. |
| [getFont()](#getFont--) | Visszaadja vagy beállítja a bekezdés jelölő betűtípusát öröklődés nélkül. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a bekezdés jelölő betűtípusát öröklődés nélkül. |
| [getHeight()](#getHeight--) | Visszaadja vagy beállítja a bekezdés jelölő magasságát öröklődés nélkül. |
| [setHeight(float value)](#setHeight-float-) | Visszaadja vagy beállítja a bekezdés jelölő magasságát öröklődés nélkül. |
| [getColor()](#getColor--) | Visszaadja a bekezdés jelölő színformátumát öröklődés nélkül. |
| [getPicture()](#getPicture--) | Visszaadja a bekezdésben jelölőként használt képet öröklődés nélkül. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Visszaadja vagy beállítja az első számot, amely a számozott jelölőcsoporthoz használatos öröklődés nélkül. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Visszaadja vagy beállítja az első számot, amely a számozott jelölőcsoporthoz használatos öröklődés nélkül. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Visszaadja vagy beállítja a számozott jelölő stílusát öröklődés nélkül. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Visszaadja vagy beállítja a számozott jelölő stílusát öröklődés nélkül. |
| [isBulletHardColor()](#isBulletHardColor--) | Megállapítja, hogy a jelölőnek saját színe van-e, vagy örökli azt a bekezdés első részletétől. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Megállapítja, hogy a jelölőnek saját színe van-e, vagy örökli azt a bekezdés első részletétől. |
| [isBulletHardFont()](#isBulletHardFont--) | Megállapítja, hogy a jelölőnek saját betűtípusa van-e, vagy örökli azt a bekezdés első részletétől. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Megállapítja, hogy a jelölőnek saját betűtípusa van-e, vagy örökli azt a bekezdés első részletétől. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Behúzás és BalMargó számára, ha a jelölők engedélyezve vannak (ahogy a PowerPoint teszi, ha engedélyezzük a bekezdés jelölőket/számozást). |
| [getEffective()](#getEffective--) | Lekéri a hatékony jelölő formázási adatokat az öröklődés alkalmazásával. |
### getType() {#getType--}
```
public abstract byte getType()
```


Visszaadja vagy beállítja a bekezdés jelölő típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Visszatér:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Visszaadja vagy beállítja a bekezdés jelölő típusát öröklődés nélkül. Olvasás/írás [BulletType](../../com.aspose.slides/bullettype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Visszaadja vagy beállítja a bekezdés jelölő karakterét öröklődés nélkül. Olvasás/írás char.

**Visszatér:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Visszaadja vagy beállítja a bekezdés jelölő karakterét öröklődés nélkül. Olvasás/írás char.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Visszaadja vagy beállítja a bekezdés jelölő betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Visszaadja vagy beállítja a bekezdés jelölő betűtípusát öröklődés nélkül. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Visszaadja vagy beállítja a bekezdés jelölő magasságát öröklődés nélkül. A Float.NaN érték azt jelenti, hogy a jelölő örökli a magasságot a bekezdés első részletétől. Olvasás/írás float.

**Visszatér:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Visszaadja vagy beállítja a bekezdés jelölő magasságát öröklődés nélkül. A Float.NaN érték azt jelenti, hogy a jelölő örökli a magasságot a bekezdés első részletétől. Olvasás/írás float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Visszaadja a bekezdés jelölő színformátumát öröklődés nélkül. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Visszaadja a bekezdésben jelölőként használt képet öröklődés nélkül. Csak olvasható [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Visszatér:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Visszaadja vagy beállítja az első számot, amely a számozott jelölőcsoporthoz használatos öröklődés nélkül. Olvasás/írás short.

**Visszatér:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Visszaadja vagy beállítja az első számot, amely a számozott jelölőcsoporthoz használatos öröklődés nélkül. Olvasás/írás short.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Visszaadja vagy beállítja a számozott jelölő stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Visszatér:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Visszaadja vagy beállítja a számozott jelölő stílusát öröklődés nélkül. Olvasás/írás [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Megállapítja, hogy a jelölőnek saját színe van-e, vagy örökli azt a bekezdés első részletétől. **NullableBool\#True** ha a jelölőnek saját színe van, és **NullableBool\#False** ha a jelölő a bekezdés első részletétől örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Megállapítja, hogy a jelölőnek saját színe van-e, vagy örökli azt a bekezdés első részletétől. **NullableBool\#True** ha a jelölőnek saját színe van, és **NullableBool\#False** ha a jelölő a bekezdés első részletétől örökli a színt. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Megállapítja, hogy a jelölőnek saját betűtípusa van-e, vagy örökli azt a bekezdés első részletétől. **NullableBool\#True** ha a jelölőnek saját betűtípusa van, és **NullableBool\#False** ha a jelölő a bekezdés első részletétől örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Megállapítja, hogy a jelölőnek saját betűtípusa van-e, vagy örökli azt a bekezdés első részletétől. **NullableBool\#True** ha a jelölőnek saját betűtípusa van, és **NullableBool\#False** ha a jelölő a bekezdés első részletétől örökli a betűtípust. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Behúzás és BalMargó számára, ha a jelölők engedélyezve vannak (ahogy a PowerPoint teszi, ha engedélyezzük a bekezdés jelölőket/számozást). Ha a jelölők le vannak tiltva, akkor csak visszaállítja a bekezdés Behúzást és BalMargót (ahogy a PowerPoint teszi, ha letiltja a bekezdés jelölőket/számozást). Az eltolások a jelenlegi jelölő kontextusra – IBulletFormat.Type, .NumberedBulletStyle és az első részlet betűmagassága – vonatkozóan kerülnek alkalmazásra. A nem nulla behúzási eltolások a jelenlegi bekezdés hatékony Behúzására és BalMargójára vonatkoznak (az eredményértékek helyi értékekké válnak).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Lekéri a hatékony jelölő formázási adatokat az öröklődés alkalmazásával.

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


**Visszatér:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).