---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Deze klasse bevat de alinea-opmaak-eigenschappen.
type: docs
url: /nl/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Deze klasse bevat de alinea-opmaak-eigenschappen. In tegenstelling tot [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om de alinea-opmaak-eigenschappen van een specifieke alinea op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, waardoor u in de meeste gevallen waarden krijgt die “onbepaald” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief overgeërfde waarden, te verkrijgen, moet u de [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective)-methode gebruiken die een [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instantie retourneert.
## Methoden

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Retourneert het opsommingstekenformaat van de alinea. |
| [getDepth()](#getDepth--) | Retourneert of stelt de diepte van de alinea in. |
| [setDepth(short value)](#setDepth-short-) | Retourneert of stelt de diepte van de alinea in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de tekstuitlijning in een alinea zonder overerving. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de tekstuitlijning in een alinea zonder overerving. |
| [getSpaceWithin()](#getSpaceWithin--) | Retourneert of stelt de afstand tussen basislijnen in een alinea in. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retourneert of stelt de afstand tussen basislijnen in een alinea in. |
| [getSpaceBefore()](#getSpaceBefore--) | Retourneert of stelt de ruimte vóór de eerste regel in een alinea zonder overerving. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retourneert of stelt de ruimte vóór de eerste regel in een alinea zonder overerving. |
| [getSpaceAfter()](#getSpaceAfter--) | Retourneert of stelt de ruimte na de laatste regel in een alinea zonder overerving. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retourneert of stelt de ruimte na de laatste regel in een alinea zonder overerving. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de Oost-Azia-regelafbreking in een alinea wordt gebruikt. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Bepaalt of de Oost-Azia-regelafbreking in een alinea wordt gebruikt. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of van rechts-naar-links schrijven in een alinea wordt gebruikt. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Bepaalt of van rechts-naar-links schrijven in een alinea wordt gebruikt. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of hangende interpunctie in een alinea wordt gebruikt. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Bepaalt of hangende interpunctie in een alinea wordt gebruikt. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linker marge in een alinea zonder overerving. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retourneert of stelt de linker marge in een alinea zonder overerving. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechter marge in een alinea zonder overerving. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retourneert of stelt de rechter marge in een alinea zonder overvesting. |
| [getIndent()](#getIndent--) | Retourneert of stelt de eerste-regel-insprong/hangende-insprong van de alinea in zonder overerving. |
| [setIndent(float value)](#setIndent-float-) | Retourneert of stelt de eerste-regel-insprong/hangende-insprong van de alinea in zonder overerving. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. |
| [getTabs()](#getTabs--) | Retourneert de tabulaties van een alinea. |
| [getFontAlignment()](#getFontAlignment--) | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retourneert het standaard-gedeelte-formaat van een alinea. |
| [getEffective()](#getEffective--) | Haalt effectieve alinea-opmaak-gegevens op met de overerving toegepast. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Retourneert het opsommingstekenformaat van de alinea. Alleen-lezen [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retourneert:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Lezen/Schrijven short.

**Retourneert:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Lezen/Schrijven short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Retourneert of stelt de tekstuitlijning in een alinea zonder overerving. Lezen/Schrijven [TextAlignment](../../com.aspose.slides/textalignment).

**Retourneert:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Retourneert of stelt de tekstuitlijning in een alinea zonder overerving. Lezen/Schrijven [TextAlignment](../../com.aspose.slides/textalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Retourneert of stelt de afstand tussen basislijnen in een alinea in. Een positieve waarde betekent een percentage, een negatieve waarde de grootte in punten. Geen overerving toegepast. Lezen/Schrijven float.

**Retourneert:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Retourneert of stelt de afstand tussen basislijnen in een alinea in. Een positieve waarde betekent een percentage, een negatieve waarde de grootte in punten. Geen overerving toegepast. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Retourneert of stelt de ruimte vóór de eerste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten. Lezen/Schrijven float.

**Retourneert:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Retourneert of stelt de ruimte vóór de eerste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Retourneert of stelt de ruimte na de laatste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten. Lezen/Schrijven float.

**Retourneert:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Retourneert of stelt de ruimte na de laatste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Bepaalt of de Oost-Azia-regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Bepaalt of de Oost-Azia-regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Bepaalt of van rechts-naar-links schrijven in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Bepaalt of van rechts-naar-links schrijven in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Bepaalt of hangende interpunctie in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Bepaalt of hangende interpunctie in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Retourneert of stelt de linker marge in een alinea zonder overerving. Lezen/Schrijven float.

**Retourneert:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Retourneert of stelt de linker marge in een alinea zonder overerving. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Retourneert of stelt de rechter marge in een alinea zonder overerving. Lezen/Schrijven float.

**Retourneert:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Retourneert of stelt de rechter marge in een alinea zonder overerving. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Retourneert of stelt de eerste-regel-insprong/hangende-insprong van de alinea in zonder overerving. Een hangende-insprong kan met negatieve waarden worden gedefinieerd. Lezen/Schrijven float.

**Retourneert:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Retourneert of stelt de eerste-regel-insprong/hangende-insprong van de alinea in zonder overerving. Een hangende-insprong kan met negatieve waarden worden gedefinieerd. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. Lezen/Schrijven float.

**Retourneert:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Retourneert de tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [ITabCollection](../../com.aspose.slides/itabcollection).

**Retourneert:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving. Lezen/Schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Retourneert:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving. Lezen/Schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Retourneert het standaard-gedeelte-formaat van een alinea. Geen overerving toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Haalt effectieve alinea-opmaak-gegevens op met de overerving toegepast.

**Retourneert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).