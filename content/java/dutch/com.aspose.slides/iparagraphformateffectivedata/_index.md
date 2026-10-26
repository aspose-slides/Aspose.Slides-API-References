---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Onveranderlijk object dat effectieve alinea-opmaak eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Onveranderlijk object dat effectieve alinea-opmaak eigenschappen bevat.

--------------------

Deze interface wordt samen met de [IParagraphFormat](../../com.aspose.slides/iparagraphformat) interface gebruikt om effectieve opmaakwaarden met toepassing van erfelijkheid terug te geven.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBullet()](#getBullet--) | Geeft een opsommingstekenindeling van een alinea terug. |
| [getDepth()](#getDepth--) | Geeft de diepte van een alinea terug. |
| [getAlignment()](#getAlignment--) | Geeft de tekstuitlijning in een alinea terug. |
| [getSpaceWithin()](#getSpaceWithin--) | Geeft de hoeveelheid ruimte tussen basisregels in een alinea terug. |
| [getSpaceBefore()](#getSpaceBefore--) | Geeft de hoeveelheid ruimte vóór de eerste regel in een alinea terug. |
| [getSpaceAfter()](#getSpaceAfter--) | Geeft de hoeveelheid ruimte na de laatste regel in een alinea terug. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de Oost-Aziatische regelafbreking in een alinea wordt gebruikt. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of van rechts naar links schrijven in een alinea wordt gebruikt. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of hangende interpunctie in een alinea wordt gebruikt. |
| [getMarginLeft()](#getMarginLeft--) | Geeft de linker marge in een alinea terug. |
| [getMarginRight()](#getMarginRight--) | Geeft de rechter marge in een alinea terug. |
| [getIndent()](#getIndent--) | Geeft de eerste regel insprong/hangende insprong van een alinea terug. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Geeft de standaard tabulatiegrootte terug. |
| [getTabs()](#getTabs--) | Geeft de tabulaties van een alinea terug. |
| [getFontAlignment()](#getFontAlignment--) | Geeft een lettertype-uitlijning in een alinea terug. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Geeft het standaard gedeelte-indeling van een alinea terug. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Geeft een opsommingstekenindeling van een alinea terug. Alleen-lezen [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Geeft de diepte van een alinea terug. Alleen-lezen short.

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Geeft de tekstuitlijning in een alinea terug. Alleen-lezen [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Geeft de hoeveelheid ruimte tussen basisregels in een alinea terug. Alleen-lezen float.

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Geeft de hoeveelheid ruimte vóór de eerste regel in een alinea terug. Alleen-lezen float.

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Geeft de hoeveelheid ruimte na de laatste regel in een alinea terug. Alleen-lezen float.

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Bepaalt of de Oost-Aziatische regelafbreking in een alinea wordt gebruikt. Alleen-lezen boolean.

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Bepaalt of van rechts naar links schrijven in een alinea wordt gebruikt. Alleen-lezen boolean.

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. Alleen-lezen boolean.

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Bepaalt of hangende interpunctie in een alinea wordt gebruikt. Alleen-lezen boolean.

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Geeft de linker marge in een alinea terug. Alleen-lezen float.

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Geeft de rechter marge in een alinea terug. Alleen-lezen float.

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Geeft de eerste regel insprong/hangende insprong van een alinea terug. Hangende insprong kan met negatieve waarden worden gedefinieerd. Alleen-lezen float.

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Geeft de standaard tabulatiegrootte terug. Alleen-lezen float.

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Geeft de tabulaties van een alinea terug. Alleen-lezen ITabEffectiveData[].

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Geeft een lettertype-uitlijning in een alinea terug. Alleen-lezen [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Geeft het standaard gedeelte-indeling van een alinea terug. Alleen-lezen [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)