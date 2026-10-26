---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /nl/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Deze klasse bevat de alineavormeigenschappen. In tegenstelling tot [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse beschrijfbaar.

--------------------

Deze klasse wordt gebruikt om de voor een specifieke alinea gedefinieerde alineavormeigenschappen op te halen en te bewerken. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, waardoor je in de meeste gevallen waarden krijgt die “onbepaald” betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet je de [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective)-methode gebruiken die een [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instantie retourneert.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBullet()](#getBullet--) | Retourneert het opsommingstekenformaat van de alinea. |
| [getDepth()](#getDepth--) | Retourneert of stelt de diepte van de alinea in. |
| [setDepth(short value)](#setDepth-short-) | Retourneert of stelt de diepte van de alinea in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. |
| [getSpaceWithin()](#getSpaceWithin--) | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. |
| [getSpaceBefore()](#getSpaceBefore--) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder overerving. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder overerving. |
| [getSpaceAfter()](#getSpaceAfter--) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder overerving. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder overerving. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of Rechts-naar-links schrijven wordt gebruikt in een alinea. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Bepaalt of Rechts-naar-links schrijven wordt gebruikt in een alinea. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge in een alinea in zonder overerving. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retourneert of stelt de linkermarge in een alinea in zonder overerving. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge in een alinea in zonder overerving. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retourneert of stelt de rechtermarge in een alinea in zonder overerving. |
| [getIndent()](#getIndent--) | Retourneert of stelt de eerste regel insprong/hangende insprong van de alinea in zonder overerving. |
| [setIndent(float value)](#setIndent-float-) | Retourneert of stelt de eerste regel insprong/hangende insprong van de alinea in zonder overerving. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retourneert of stelt de standaardtabulatiegrootte in zonder overerving. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retourneert of stelt de standaardtabulatiegrootte in zonder overerving. |
| [getTabs()](#getTabs--) | Retourneert tabulaties van een alinea. |
| [getFontAlignment()](#getFontAlignment--) | Retourneert of stelt een lettertype-uitlijning in een alinea in zonder overerving. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retourneert of stelt een lettertype-uitlijning in een alinea in zonder overerving. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retourneert het standaarddeelformaat van een alinea. |
| [getEffective()](#getEffective--) | Haalt effectieve alineavormgevinggegevens op met de overerving toegepast. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Retourneert het opsommingstekenformaat van de alinea. Alleen-lezen [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retour:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent een ongedefinieerde waarde. Lezen/schrijven short.

**Retour:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent een ongedefinieerde waarde. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

**Retour:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Positieve waarde betekent een percentage, negatieve een grootte in punten. Geen overerving toegepast. Lezen/schrijven float.

**Retour:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Positieve waarde betekent een percentage, negatieve een grootte in punten. Geen overerving toegepast. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Retour:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Retour:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Bepaalt of Rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Bepaalt of Rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Retourneert of stelt de linkermarge in een alinea in zonder overerving. Lezen/schrijven float.

**Retour:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Retourneert of stelt de linkermarge in een alinea in zonder overerving. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Retourneert of stelt de rechtermarge in een alinea in zonder overerving. Lezen/schrijven float.

**Retour:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Retourneert of stelt de rechtermarge in een alinea in zonder overerving. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Retourneert of stelt de eerste regel insprong/hangende insprong van de alinea in zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lezen/schrijven float.

**Retour:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Retourneert of stelt de eerste regel insprong/hangende insprong van de alinea in zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Retourneert of stelt de standaardtabulatiegrootte in zonder overerving. Lezen/schrijven float.

**Retour:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Retourneert of stelt de standaardtabulatiegrootte in zonder overerving. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Retourneert tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [ITabCollection](../../com.aspose.slides/itabcollection).

**Retour:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Retourneert of stelt een lettertype-uitlijning in een alinea in zonder overerving. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Retour:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Retourneert of stelt een lettertype-uitlijning in een alinea in zonder overerving. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Retourneert het standaarddeelformaat van een alinea. Geen overerving toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Haalt effectieve alineavormgevinggegevens op met de overerving toegepast.

**Retour:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).