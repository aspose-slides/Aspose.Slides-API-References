---
title: BulletFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar egenskaper för styckespunktsformatering.
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

Representerar styckeformat för punktlistor.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar eller ställer in punkttypen för ett stycke utan arv. |
| [setType(byte value)](#setType-byte-) | Returnerar eller ställer in punkttypen för ett stycke utan arv. |
| [getChar()](#getChar--) | Returnerar eller ställer in punkttecknet för ett stycke utan arv. |
| [setChar(char value)](#setChar-char-) | Returnerar eller ställer in punkttecknet för ett stycke utan arv. |
| [getFont()](#getFont--) | Returnerar eller ställer in punktfonten för ett stycke utan arv. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Returnerar eller ställer in punktfonten för ett stycke utan arv. |
| [getHeight()](#getHeight--) | Returnerar eller ställer in punktens höjd för ett stycke utan arv. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller ställer in punktens höjd för ett stycke utan arv. |
| [getColor()](#getColor--) | Returnerar färgformatet för en punkt i ett stycke utan arv. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returnerar eller ställer in det första numret som används för en grupp numrerade punkter utan arv. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returnerar eller ställer in det första numret som används för en grupp numrerade punkter utan arv. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returnerar eller ställer in stilen för en numrerad punkt utan arv. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returnerar eller ställer in stilen för en numrerad punkt utan arv. |
| [isBulletHardColor()](#isBulletHardColor--) | Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket. |
| [isBulletHardFont()](#isBulletHardFont--) | Bestämmer om punkten har eget typsnitt eller ärver det från den första delen i stycket. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bestämmer om punkten har eget typsnitt eller ärver det från den första delen i stycket. |
| [getPicture()](#getPicture--) | Returnerar bilden som används som punkt i ett stycke utan arv. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ställer in standard icke-noll förskjutningar för effektiv stycke Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör om styckespunkter/numrering aktiveras i den). |
| [getEffective()](#getEffective--) | Hämtar effektiv punktformateringsdata med ärvda inställningar tillämpade. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Returnerar eller ställer in punkttypen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Returnerar:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Returnerar eller ställer in punkttypen för ett stycke utan arv. Läs/skriv [BulletType](../../com.aspose.slides/bullettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```


Returnerar eller ställer in punkttecknet för ett stycke utan arv. Läs/skriv  char .

**Returnerar:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Returnerar eller ställer in punkttecknet för ett stycke utan arv. Läs/skriv  char .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```


Returnerar eller ställer in punktfonten för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Returnerar eller ställer in punktfonten för ett stycke utan arv. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returnerar eller ställer in punktens höjd för ett stycke utan arv. Värdet Float.NaN betyder att punkten ärver höjden från den första delen i stycket. Läs/skriv  float .

--------------------

Ett negativt höjdvärde betyder att höjden anges i punkter och ett positivt värde betyder att höjden är en procentsats av den omgivande texten.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returnerar eller ställer in punktens höjd för ett stycke utan arv. Värdet Float.NaN betyder att punkten ärver höjden från den första delen i stycket. Läs/skriv  float .

--------------------

Ett negativt höjdvärde betyder att höjden anges i punkter och ett positivt värde betyder att höjden är en procentsats av den omgivande texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returnerar färgformatet för en punkt i ett stycke utan arv. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Returnerar eller ställer in det första numret som används för en grupp numrerade punkter utan arv. Läs/skriv  short .

**Returnerar:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Returnerar eller ställer in det första numret som används för en grupp numrerade punkter utan arv. Läs/skriv  short .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Returnerar eller ställer in stilen för en numrerad punkt utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returnerar:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Returnerar eller ställer in stilen för en numrerad punkt utan arv. Läs/skriv [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket. **NullableBool.True** om punkten har egen färg och **NullableBool.False** om punkten ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket. **NullableBool.True** om punkten har egen färg och **NullableBool.False** om punkten ärver färg från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Bestämmer om punkten har eget typsnitt eller ärver det från den första delen i stycket. **NullableBool.True** om punkten har eget typsnitt och **NullableBool.False** om punkten ärver typsnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Bestämmer om punkten har eget typsnitt eller ärver det från den första delen i stycket. **NullableBool.True** om punkten har eget typsnitt och **NullableBool.False** om punkten ärver typsnitt från den första delen i stycket. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Returnerar bilden som används som punkt i ett stycke utan arv. Endast läsning [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returnerar:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Ställer in standard icke-noll förskjutningar för effektiv stycke Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör om styckespunkter/numrering aktiveras i den). Om punkter är inaktiverade återställer bara stycke Indent och MarginLeft (som PowerPoint gör om styckespunkter/numrering inaktiveras i den). Indent-förskjutningar tillämpas med hänsyn till den aktuella punktkontexten – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll Indent-förskjutningar tillämpas på effektiv Indent och MarginLeft för aktuellt stycke (gör resultatinvärdena lokala).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Hämtar effektiv punktformateringsdata med ärvda inställningar tillämpade.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Endast läsning long.

**Returnerar:**
long