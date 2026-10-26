---
title: IBulletFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de opmaak-eigenschappen van alinea-opsommingstekens voor.
type: docs
url: /nl/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Stelt de opmaak-eigenschappen van alinea-opsommingstekens voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Geeft het opsommingsteken-type van een alinea terug of stelt het in zonder overerving. |
| [setType(byte value)](#setType-byte-) | Geeft het opsommingsteken-type van een alinea terug of stelt het in zonder overerving. |
| [getChar()](#getChar--) | Geeft het opsommingsteken-teken van een alinea terug of stelt het in zonder overerving. |
| [setChar(char value)](#setChar-char-) | Geeft het opsommingsteken-teken van een alinea terug of stelt het in zonder overerving. |
| [getFont()](#getFont--) | Geeft het opsommingsteken-lettertype van een alinea terug of stelt het in zonder overerving. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Geeft het opsommingsteken-lettertype van een alinea terug of stelt het in zonder overerving. |
| [getHeight()](#getHeight--) | Geeft de opsommingsteken-hoogte van een alinea terug of stelt het in zonder overerving. |
| [setHeight(float value)](#setHeight-float-) | Geeft de opsommingsteken-hoogte van een alinea terug of stelt het in zonder overerving. |
| [getColor()](#getColor--) | Geeft het kleurformaat van een opsommingsteken van een alinea terug zonder overerving. |
| [getPicture()](#getPicture--) | Geeft de afbeelding die als opsommingsteken wordt gebruikt in een alinea zonder overerving terug. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Geeft het eerste nummer dat wordt gebruikt voor een groep genummerde opsommingstekens terug of stelt het in zonder overerving. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Geeft het eerste nummer dat wordt gebruikt voor een groep genummerde opsommingstekens terug of stelt het in zonder overerving. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Geeft de stijl van een genummerd opsommingsteken terug of stelt het in zonder overerving. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Geeft de stijl van een genummerd opsommingsteken terug of stelt het in zonder overerving. |
| [isBulletHardColor()](#isBulletHardColor--) | Bepaalt of het opsommingsteken een eigen kleur heeft of deze erft van het eerste deel in de alinea. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bepaalt of het opsommingsteken een eigen kleur heeft of deze erft van het eerste deel in de alinea. |
| [isBulletHardFont()](#isBulletHardFont--) | Bepaalt of het opsommingsteken een eigen lettertype heeft of dit erft van het eerste deel in de alinea. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bepaalt of het opsommingsteken een eigen lettertype heeft of dit erft van het eerste deel in de alinea. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Stelt standaard niet-nul verschuivingen in voor effectieve alinea-insprong en marge-links wanneer opsommingstekens zijn ingeschakeld (zoals PowerPoint doet bij inschakelen van alinea-opsomming/nummering). |
| [getEffective()](#getEffective--) | Haalt effectieve opsommingsteken-opmaakdata op met de toegepaste overerving. |

### getType() {#getType--}
```
public abstract byte getType()
```

Geeft het opsommingsteken-type van een alinea terug of stelt het in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Retour:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Geeft het opsommingsteken-type van een alinea terug of stelt het in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Geeft het opsommingsteken-teken van een alinea terug of stelt het in zonder overerving. Lezen/schrijven char.

**Retour:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Geeft het opsommingsteken-teken van een alinea terug of stelt het in zonder overerving. Lezen/schrijven char.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Geeft het opsommingsteken-lettertype van een alinea terug of stelt het in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Geeft het opsommingsteken-lettertype van een alinea terug of stelt het in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Geeft de opsommingsteken-hoogte van een alinea terug of stelt het in zonder overerving. De waarde Float.NaN bepaalt dat het opsommingsteken de hoogte erft van het eerste deel in de alinea. Lezen/schrijven float.

**Retour:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Geeft de opsommingsteken-hoogte van een alinea terug of stelt het in zonder overerving. De waarde Float.NaN bepaalt dat het opsommingsteken de hoogte erft van het eerste deel in de alinea. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Geeft het kleurformaat van een opsommingsteken van een alinea terug zonder overerving. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Geeft de afbeelding die als opsommingsteken wordt gebruikt in een alinea zonder overerving terug. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retour:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Geeft het eerste nummer dat wordt gebruikt voor een groep genummerde opsommingstekens terug of stelt het in zonder overerving. Lezen/schrijven short.

**Retour:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Geeft het eerste nummer dat wordt gebruikt voor een groep genummerde opsommingstekens terug of stelt het in zonder overerving. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Geeft de stijl van een genummerd opsommingsteken terug of stelt het in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Retour:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Geeft de stijl van een genummerd opsommingsteken terug of stelt het in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Bepaalt of het opsommingsteken een eigen kleur heeft of deze erft van het eerste deel in de alinea. **NullableBool\#True** als het opsommingsteken een eigen kleur heeft en **NullableBool\#False** als het opsommingsteken de kleur erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Bepaalt of het opsommingsteken een eigen kleur heeft of deze erft van het eerste deel in de alinea. **NullableBool\#True** als het opsommingsteken een eigen kleur heeft en **NullableBool\#False** als het opsommingsteken de kleur erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Bepaalt of het opsommingsteken een eigen lettertype heeft of dit erft van het eerste deel in de alinea. **NullableBool\#True** als het opsommingsteken een eigen lettertype heeft en **NullableBool\#False** als het opsommingsteken het lettertype erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Bepaalt of het opsommingsteken een eigen lettertype heeft of dit erft van het eerste deel in de alinea. **NullableBool\#True** als het opsommingsteken een eigen lettertype heeft en **NullableBool\#False** als het opsommingsteken het lettertype erft van het eerste deel in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Stelt standaard niet-nul verschuivingen in voor effectieve alinea-insprong en marge-links wanneer opsommingstekens zijn ingeschakeld (zoals PowerPoint doet bij inschakelen van alinea-opsomming/nummering). Als opsommingstekens zijn uitgeschakeld, worden alleen de alinea-insprong en marge-links gereset (zoals PowerPoint doet bij uitschakelen van alinea-opsomming/nummering). De verschuivingen worden toegepast met betrekking tot de huidige opsommingsteken-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste deel. Niet-nul verschuivingen worden toegepast op de effectieve insprong en marge-links van de huidige alinea (zodat de resulterende waarden lokale waarden worden).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Haalt effectieve opsommingsteken-opmaakdata op met de toegepaste overerving.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).