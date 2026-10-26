---
title: BulletFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de bullet-opmaak eigenschappen van een alinea voor.
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

Stelt de bullet-opmaak eigenschappen van een alinea voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert of stelt het bullettype van een alinea zonder overerving in. |
| [setType(byte value)](#setType-byte-) | Retourneert of stelt het bullettype van een alinea zonder overerving in. |
| [getChar()](#getChar--) | Retourneert of stelt het bullet-teken van een alinea zonder overerving in. |
| [setChar(char value)](#setChar-char-) | Retourneert of stelt het bullet-teken van een alinea zonder overerving in. |
| [getFont()](#getFont--) | Retourneert of stelt het bullet-lettertype van een alinea zonder overerving in. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Retourneert of stelt het bullet-lettertype van een alinea zonder overerving in. |
| [getHeight()](#getHeight--) | Retourneert of stelt de bullethoogte van een alinea zonder overerving in. |
| [setHeight(float value)](#setHeight-float-) | Retourneert of stelt de bullethoogte van een alinea zonder overerving in. |
| [getColor()](#getColor--) | Retourneert het kleurformaat van een bullet van een alinea zonder overerving. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. |
| [isBulletHardColor()](#isBulletHardColor--) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. |
| [isBulletHardFont()](#isBulletHardFont--) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. |
| [getPicture()](#getPicture--) | Retourneert de afbeelding die als bullet wordt gebruikt in een alinea zonder overerving. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Stelt standaard niet-nul verschuivingen in voor effectieve alinea-inspringing en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet bij inschakelen van alinea-bullets/nummering). |
| [getEffective()](#getEffective--) | Haalt effectieve bullet-opmaakgegevens op met de toepaste overerving. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Retourneert of stelt het bullettype van een alinea zonder overerving in. Lezen/Schrijven [BulletType](../../com.aspose.slides/bullettype).

**Retour:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Retourneert of stelt het bullettype van een alinea zonder overerving in. Lezen/Schrijven [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```


Retourneert of stelt het bullet-teken van een alinea zonder overerving in. Lezen/Schrijven  char .

**Retour:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Retourneert of stelt het bullet-teken van een alinea zonder overerving in. Lezen/Schrijven  char .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```


Retourneert of stelt het bullet-lettertype van een alinea zonder overerving in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Retourneert of stelt het bullet-lettertype van een alinea zonder overerving in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Retourneert of stelt de bullethoogte van een alinea zonder overerving in. De waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Lezen/Schrijven  float .

--------------------

Een negatieve hoogte-waarde betekent dat de hoogte wordt opgegeven in punten en een positieve waarde betekent dat de hoogte een percentage is van de omringende tekst.

**Retour:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Retourneert of stelt de bullethoogte van een alinea zonder overerving in. De waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Lezen/Schrijven  float .

--------------------

Een negatieve hoogte-waarde betekent dat de hoogte wordt opgegeven in punten en een positieve waarde betekent dat de hoogte een percentage is van de omringende tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Retourneert het kleurformaat van een bullet van een alinea zonder overerving. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Lezen/Schrijven  short .

**Retour:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Lezen/Schrijven  short .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. Lezen/Schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retour:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. Lezen/Schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool.True** als de bullet een eigen kleur heeft en **NullableBool.False** als de bullet de kleur erft van het eerste gedeelte in de alinea. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool.True** als de bullet een eigen kleur heeft en **NullableBool.False** als de bullet de kleur erft van het eerste gedeelte in de alinea. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. **NullableBool.True** als de bullet een eigen lettertype heeft en **NullableBool.False** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. **NullableBool.True** als de bullet een eigen lettertype heeft en **NullableBool.False** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Retourneert de afbeelding die als bullet wordt gebruikt in een alinea zonder overerving. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retour:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Stelt standaard niet-nul verschuivingen in voor effectieve alinea-inspringing en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet bij inschakelen van alinea-bullets/nummering). Als bullets zijn uitgeschakeld, worden de alinea-inspringing en MarginLeft gewoon gereset (zoals PowerPoint doet bij uitschakelen van alinea-bullets/nummering). Inspring-verschuivingen worden toegepast met betrekking tot de huidige bullet-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul inspring-verschuivingen worden toegepast op de effectieve Inspringing en MarginLeft van de huidige alinea (maak resulterende waarden lokaal).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Haalt effectieve bullet-opmaakgegevens op met de toepaste overerving.

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