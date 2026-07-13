---
title: BulletFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt de opmaak van alinea-bullet-eigenschappen.
type: docs
url: /nl/com.aspose.slides/bulletformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Vertegenwoordigt de opmaak van alinea-bullet-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Geeft de bullet-type van een alinea terug of stelt deze in zonder overerving. |
| [setType(byte value)](#setType-byte-) | Geeft de bullet-type van een alinea terug of stelt deze in zonder overerving. |
| [getChar()](#getChar--) | Geeft het bullet-teken van een alinea terug of stelt dit in zonder overerving. |
| [setChar(char value)](#setChar-char-) | Geeft het bullet-teken van een alinea terug of stelt dit in zonder overerving. |
| [getFont()](#getFont--) | Geeft het bullet-lettertype van een alinea terug of stelt dit in zonder overerving. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Geeft het bullet-lettertype van een alinea terug of stelt dit in zonder overerving. |
| [getHeight()](#getHeight--) | Geeft de bullet-hoogte van een alinea terug of stelt deze in zonder overerving. |
| [setHeight(float value)](#setHeight-float-) | Geeft de bullet-hoogte van een alinea terug of stelt deze in zonder overerving. |
| [getColor()](#getColor--) | Geeft het kleurformaat van een bullet van een alinea terug zonder overerving. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Geeft het eerste getal dat wordt gebruikt voor een groep genummerde bullets terug of stelt dit in zonder overerving. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Geeft het eerste getal dat wordt gebruikt voor een groep genummerde bullets terug of stelt dit in zonder overerving. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Geeft de stijl van een genummerde bullet terug of stelt deze in zonder overerving. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Geeft de stijl van een genummerde bullet terug of stelt deze in zonder overerving. |
| [isBulletHardColor()](#isBulletHardColor--) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste deel in de alinea. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste deel in de alinea. |
| [isBulletHardFont()](#isBulletHardFont--) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste deel in de alinea. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste deel in de alinea. |
| [getPicture()](#getPicture--) | Geeft de afbeelding die als bullet wordt gebruikt in een alinea terug zonder overerving. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Stelt standaard niet-nul verschuivingen in voor effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet als alinea-bullets/nummering zijn ingeschakeld). |
| [getEffective()](#getEffective--) | Haalt de effectieve bullet-opmaakgegevens op met de overerving toegepast. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Geeft de bullet-type van een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Retour:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Geeft de bullet-type van een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Geeft het bullet-teken van een alinea terug of stelt dit in zonder overerving. Lezen/schrijven  char .

**Retour:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Geeft het bullet-teken van een alinea terug of stelt dit in zonder overerving. Lezen/schrijven  char .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Geeft het bullet-lettertype van een alinea terug of stelt dit in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Geeft het bullet-lettertype van een alinea terug of stelt dit in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Geeft de bullet-hoogte van een alinea terug of stelt deze in zonder overerving. Waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste deel in de alinea. Lezen/schrijven  float .

--------------------

Een negatieve hoogtedwaarde betekent dat de hoogte in punten wordt opgegeven en een positieve waarde betekent dat de hoogte een percentage van de omringende tekst is.

**Retour:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Geeft de bullet-hoogte van een alinea terug of stelt deze in zonder overerving. Waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste deel in de alinea. Lezen/schrijven  float .

--------------------

Een negatieve hoogtedwaarde betekent dat de hoogte in punten wordt opgegeven en een positieve waarde betekent dat de hoogte een percentage van de omringende tekst is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Geeft het kleurformaat van een bullet van een alinea terug zonder overerving. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Geeft het eerste getal dat wordt gebruikt voor een groep genummerde bullets terug of stelt dit in zonder overerving. Lezen/schrijven  short .

**Retour:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Geeft het eerste getal dat wordt gebruikt voor een groep genummerde bullets terug of stelt dit in zonder overerving. Lezen/schrijven  short .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Geeft de stijl van een genummerde bullet terug of stelt deze in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retour:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Geeft de stijl van een genummerde bullet terug of stelt deze in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste deel in de alinea. **NullableBool.True** als de bullet een eigen kleur heeft en **NullableBool.False** als de bullet de kleur erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste deel in de alinea. **NullableBool.True** als de bullet een eigen kleur heeft en **NullableBool.False** als de bullet de kleur erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste deel in de alinea. **NullableBool.True** als de bullet een eigen lettertype heeft en **NullableBool.False** als de bullet het lettertype erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste deel in de alinea. **NullableBool.True** als de bullet een eigen lettertype heeft en **NullableBool.False** als de bullet het lettertype erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Geeft de afbeelding die als bullet wordt gebruikt in een alinea terug zonder overerving. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retour:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Stelt standaard niet-nul verschuivingen in voor effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet als alinea-bullets/nummering zijn ingeschakeld). Als bullets zijn uitgeschakeld worden alleen alinea-Indent en MarginLeft gereset (zoals PowerPoint doet als alinea-bullets/nummering worden uitgeschakeld). Indent-verschuivingen worden toegepast met betrekking tot de huidige bullet-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste deel. Niet-nul indent-verschuivingen worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (maakt dat resultaatwaarden lokale waarden zijn).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Haalt de effectieve bullet-opmaakgegevens op met de overerving toegepast.

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

**Retour:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Een [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long