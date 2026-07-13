---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt de bullet-opmaak van een alinea.
type: docs
url: /nl/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Stelt de bullet-opmaak van een alinea voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert of stelt het bullettype van een alinea in zonder overerving. |
| [setType(byte value)](#setType-byte-) | Retourneert of stelt het bullettype van een alinea in zonder overerving. |
| [getChar()](#getChar--) | Retourneert of stelt het bulletteken van een alinea in zonder overerving. |
| [setChar(char value)](#setChar-char-) | Retourneert of stelt het bulletteken van een alinea in zonder overerving. |
| [getFont()](#getFont--) | Retourneert of stelt het bulletlettertype van een alinea in zonder overerving. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Retourneert of stelt het bulletlettertype van een alinea in zonder overerving. |
| [getHeight()](#getHeight--) | Retourneert of stelt de bullethoogte van een alinea in zonder overerving. |
| [setHeight(float value)](#setHeight-float-) | Retourneert of stelt de bullethoogte van een alinea in zonder overerving. |
| [getColor()](#getColor--) | Retourneert het kleurformaat van een bullet van een alinea zonder overerving. |
| [getPicture()](#getPicture--) | Retourneert de afbeelding die als bullet wordt gebruikt in een alinea zonder overerving. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. |
| [isBulletHardColor()](#isBulletHardColor--) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. |
| [isBulletHardFont()](#isBulletHardFont--) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Stelt standaard niet-nul verschuivingen in voor effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet bij het inschakelen van alinea-bullets/nummering). |
| [getEffective()](#getEffective--) | Haalt de effectieve bullet-opmaakgegevens op met de toegepaste overerving. |
### getType() {#getType--}
```
public abstract byte getType()
```

Retourneert of stelt het bullettype van een alinea in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Retourneert:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Retourneert of stelt het bullettype van een alinea in zonder overerving. Lezen/schrijven [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Retourneert of stelt het bulletteken van een alinea in zonder overerving. Lezen/schrijven char.

**Retourneert:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Retourneert of stelt het bulletteken van een alinea in zonder overerving. Lezen/schrijven char.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Retourneert of stelt het bulletlettertype van een alinea in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Retourneert of stelt het bulletlettertype van een alinea in zonder overerving. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Retourneert of stelt de bullethoogte van een alinea in zonder overerving. Waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Lezen/schrijven float.

**Retourneert:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Retourneert of stelt de bullethoogte van een alinea in zonder overerving. Waarde Float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Retourneert het kleurformaat van een bullet van een alinea zonder overerving. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Retourneert de afbeelding die als bullet wordt gebruikt in een alinea zonder overerving. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retourneert:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Lezen/schrijven short.

**Retourneert:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Retourneert of stelt het eerste nummer in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Retourneert:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Retourneert of stelt de stijl van een genummerde bullet in zonder overerving. Lezen/schrijven [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool#True** als de bullet een eigen kleur heeft en **NullableBool#False** als de bullet de kleur erft van het eerste gedeelte in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool#True** als de bullet een eigen kleur heeft en **NullableBool#False** als de bullet de kleur erft van het eerste gedeelte in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool#True** als de bullet een eigen lettertype heeft en **NullableBool#False** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Bepaalt of de bullet een eigen lettertype heeft of deze erft van het eerste gedeelte in de alinea. **NullableBool#True** als de bullet een eigen lettertype heeft en **NullableBool#False** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Stelt standaard niet-nul verschuivingen in voor effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet bij het inschakelen van alinea-bullets/nummering). Als bullets zijn uitgeschakeld, worden de alinea-Indent en MarginLeft gewoon gereset (zoals PowerPoint doet bij het uitschakelen van alinea-bullets/nummering). Indent-verschuivingen worden toegepast ten opzichte van de huidige bullet-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul indent-verschuivingen worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (zodat de resultaatwaarden lokale waarden worden).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Haalt effectieve bullet-opmaakgegevens op met de toegepaste overerving.

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


**Retourneert:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).