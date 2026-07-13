---
title: IBulletFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar paragrafens punktlistformatsegenskaper.
type: docs
url: /sv/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Representerar paragrafens punktlistformatsegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar eller anger punkttypen för ett stycke utan arv. |
| [setType(byte value)](#setType-byte-) | Returnerar eller anger punkttypen för ett stycke utan arv. |
| [getChar()](#getChar--) | Returnerar eller anger punktsymbolen för ett stycke utan arv. |
| [setChar(char value)](#setChar-char-) | Returnerar eller anger punktsymbolen för ett stycke utan arv. |
| [getFont()](#getFont--) | Returnerar eller anger punktteckensnittet för ett stycke utan arv. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Returnerar eller anger punktteckensnittet för ett stycke utan arv. |
| [getHeight()](#getHeight--) | Returnerar eller anger punktens höjd för ett stycke utan arv. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller anger punktens höjd för ett stycke utan arv. |
| [getColor()](#getColor--) | Returnerar färgformatet för en punkt i ett stycke utan arv. |
| [getPicture()](#getPicture--) | Returnerar bilden som används som punkt i ett stycke utan arv. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returnerar eller anger det första numret som används för en grupp numrerade punkter utan arv. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returnerar eller anger det första numret som används för en grupp numrerade punkter utan arv. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returnerar eller anger stilen för en numrerad punkt utan arv. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returnerar eller anger stilen för en numrerad punkt utan arv. |
| [isBulletHardColor()](#isBulletHardColor--) | Avgör om punkten har egen färg eller ärver den från den första delen i stycket. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Avgör om punkten har egen färg eller ärver den från den första delen i stycket. |
| [isBulletHardFont()](#isBulletHardFont--) | Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ställer in standardvärden för icke-noll-förskjutningar för effektiv stycke-Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör om du aktiverar styckepunkter/numrering). |
| [getEffective()](#getEffective--) | Hämtar effektiva punktformateringsdata med arv tillämpat. |
### getType() {#getType--}
```
public abstract byte getType()
```


Returnerar eller anger punkttypen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Returnerar:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Returnerar eller anger punkttypen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Returnerar eller anger punktsymbolen för ett stycke utan arv. Läs/skriv char.

**Returnerar:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Returnerar eller anger punktsymbolen för ett stycke utan arv. Läs/skriv char.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Returnerar eller anger punktteckensnittet för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Returnerar eller anger punktteckensnittet för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Returnerar eller anger punktens höjd för ett stycke utan arv. Värdet Float.NaN betyder att punktens höjd ärvs från den första delen i stycket. Läs/skriv float.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Returnerar eller anger punktens höjd för ett stycke utan arv. Värdet Float.NaN betyder att punktens höjd ärvs från den första delen i stycket. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Returnerar färgformatet för en punkt i ett stycke utan arv. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Returnerar bilden som används som punkt i ett stycke utan arv. Endast läsning [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returnerar:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Returnerar eller anger det första numret som används för en grupp numrerade punkter utan arv. Läs/skriv short.

**Returnerar:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Returnerar eller anger det första numret som används för en grupp numrerade punkter utan arv. Läs/skriv short.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Returnerar eller anger stilen för en numrerad punkt utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Returnerar:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Returnerar eller anger stilen för en numrerad punkt utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Avgör om punkten har egen färg eller ärver den från den första delen i stycket. **NullableBool\#True** om punkten har egen färg och **NullableBool\#False** om punkten ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Avgör om punkten har egen färg eller ärver den från den första delen i stycket. **NullableBool\#True** om punkten har egen färg och **NullableBool\#False** om punkten ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. **NullableBool\#True** om punkten har eget teckensnitt och **NullableBool\#False** om punkten ärver teckensnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. **NullableBool\#True** om punkten har eget teckensnitt och **NullableBool\#False** om punkten ärver teckensnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Ställer in standardvärden för icke-noll-förskjutningar för effektiv stycke-Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör om du aktiverar styckepunkter/numrering). Om punkter är inaktiverade återställs bara stycke-Indent och MarginLeft (som PowerPoint gör om du inaktiverar styckepunkter/numrering). Indent-förskjutningar tillämpas i förhållande till aktuell punktkontext – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll förskjutningar appliceras på effektiv Indent och MarginLeft för aktuellt stycke (gör resultatvärdena lokala).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Hämtar effektiva punktformateringsdata med arv tillämpat.

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


**Returnerar:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - En [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).