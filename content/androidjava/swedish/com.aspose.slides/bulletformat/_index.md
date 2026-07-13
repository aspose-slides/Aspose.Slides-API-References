---
title: BulletFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar styckets punktformateringsegenskaper.
type: docs
url: /sv/com.aspose.slides/bulletformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Representerar stycket bullet-formateringsegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar eller anger bullet-typen för ett stycke utan arv. |
| [setType(byte value)](#setType-byte-) | Returnerar eller anger bullet-typen för ett stycke utan arv. |
| [getChar()](#getChar--) | Returnerar eller anger bullet-tecknet för ett stycke utan arv. |
| [setChar(char value)](#setChar-char-) | Returnerar eller anger bullet-tecknet för ett stycke utan arv. |
| [getFont()](#getFont--) | Returnerar eller anger bullet-teckensnittet för ett stycke utan arv. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Returnerar eller anger bullet-teckensnittet för ett stycke utan arv. |
| [getHeight()](#getHeight--) | Returnerar eller anger bullet-höjden för ett stycke utan arv. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller anger bullet-höjden för ett stycke utan arv. |
| [getColor()](#getColor--) | Returnerar färgformatet för en bullet i ett stycke utan arv. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returnerar eller anger det första numret som används för en grupp numrerade bullets utan arv. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returnerar eller anger det första numret som används för en grupp numrerade bullets utan arv. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returnerar eller anger stilen för en numrerad bullet utan arv. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returnerar eller anger stilen för en numrerad bullet utan arv. |
| [isBulletHardColor()](#isBulletHardColor--) | Avgör om bullet har egen färg eller ärver den från den första delen i stycket. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Avgör om bullet har egen färg eller ärver den från den första delen i stycket. |
| [isBulletHardFont()](#isBulletHardFont--) | Avgör om bullet har eget teckensnitt eller ärver det från den första delen i stycket. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Avgör om bullet har eget teckensnitt eller ärver det från den första delen i stycket. |
| [getPicture()](#getPicture--) | Returnerar bilden som används som bullet i ett stycke utan arv. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ställer in standard-icke-nollförskjutningar för effektiv stycke-Indent och MarginLeft när bullets är aktiverade (som PowerPoint gör om du aktiverar stycket-bullets/nummerering). |
| [getEffective()](#getEffective--) | Hämtar effektiv bullet-formateringsdata med ärvda värden applicerade. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Returnerar eller anger bullet-typen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Returnerar:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Returnerar eller anger bullet-typen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Returnerar eller anger bullet-tecknet för ett stycke utan arv. Läs/skriv char .

**Returnerar:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Returnerar eller anger bullet-tecknet för ett stycke utan arv. Läs/skriv char .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Returnerar eller anger bullet-teckensnittet för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Returnerar eller anger bullet-teckensnittet för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returnerar eller anger bullet-höjden för ett stycke utan arv. Värdet Float.NaN betyder att bullet ärver höjden från den första delen i stycket. Läs/skriv float .

--------------------

Ett negativt höjdvärde betyder att höjden anges i punkter och ett positivt värde betyder att höjden är en procentsats av den omgivande texten.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returnerar eller anger bullet-höjden för ett stycke utan arv. Värdet Float.NaN betyder att bullet ärver höjden från den första delen i stycket. Läs/skriv float .

--------------------

Ett negativt höjdvärde betyder att höjden anges i punkter och ett positivt värde betyder att höjden är en procentsats av den omgivande texten.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returnerar färgformatet för en bullet i ett stycke utan arv. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Returnerar eller anger det första numret som används för en grupp numrerade bullets utan arv. Läs/skriv short .

**Returnerar:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Returnerar eller anger det första numret som används för en grupp numrerade bullets utan arv. Läs/skriv short .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Returnerar eller anger stilen för en numrerad bullet utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returnerar:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Returnerar eller anger stilen för en numrerad bullet utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Avgör om bullet har egen färg eller ärver den från den första delen i stycket. **NullableBool.True** om bullet har egen färg och **NullableBool.False** om bullet ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Avgör om bullet har egen färg eller ärver den från den första delen i stycket. **NullableBool.True** om bullet har egen färg och **NullableBool.False** om bullet ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Avgör om bullet har eget teckensnitt eller ärver det från den första delen i stycket. **NullableBool.True** om bullet har eget teckensnitt och **NullableBool.False** om bullet ärver teckensnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Avgör om bullet har eget teckensnitt eller ärver det från den första delen i stycket. **NullableBool.True** om bullet har eget teckensnitt och **NullableBool.False** om bullet ärver teckensnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Returnerar bilden som används som bullet i ett stycke utan arv. Skrivskyddad [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returnerar:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Ställer in standard-icke-nollförskjutningar för effektiv stycke-Indent och MarginLeft när bullets är aktiverade (som PowerPoint gör om du aktiverar stycket-bullets/nummerering). Om bullets är inaktiverade återställer den bara stycke-Indent och MarginLeft (som PowerPoint gör om du inaktiverar stycket-bullets/nummerering). Indent-förskjutningar tillämpas med hänsyn till aktuell bullet-kontext – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll indent-förskjutningar appliceras på effektiv Indent och MarginLeft för aktuellt stycke (gör resultatvärdena lokala).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Hämtar effektiv bullet-formateringsdata med ärvda värden applicerade.

--------------------

> ```
> Detta exempel visar hur man hämtar vissa effektiva bullet format-egenskaper.
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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) – En [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long