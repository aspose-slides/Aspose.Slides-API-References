---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Referencia
description: Immutable objektum, amely a hatékony bekezdésformázási tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Immutable objektum, amely a hatékony bekezdésformázási tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [IParagraphFormat](../../com.aspose.slides/iparagraphformat) interfésszel együtt használható a hatékony formázási értékek visszaadásához öröklődés alkalmazásával.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBullet()](#getBullet--) | Visszaad egy bekezdés felsorolásformátumát. |
| [getDepth()](#getDepth--) | Visszaad egy bekezdés mélységét. |
| [getAlignment()](#getAlignment--) | Visszaad a szöveg igazítását egy bekezdésben. |
| [getSpaceWithin()](#getSpaceWithin--) | Visszaad a sorok közötti távolságot egy bekezdésben. |
| [getSpaceBefore()](#getSpaceBefore--) | Visszaad a térközt az első sor előtt egy bekezdésben. |
| [getSpaceAfter()](#getSpaceAfter--) | Visszaad a térközt az utolsó sor után egy bekezdésben. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Megállapítja, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy jobbról balra írás irányt használják-e egy bekezdésben. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Megállapítja, hogy a latin sortörést használják-e egy bekezdésben. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Megállapítja, hogy függő írásjelet használnak-e egy bekezdésben. |
| [getMarginLeft()](#getMarginLeft--) | Visszaad a bal margót egy bekezdésben. |
| [getMarginRight()](#getMarginRight--) | Visszaad a jobb margót egy bekezdésben. |
| [getIndent()](#getIndent--) | Visszaad a bekezdés első sor behúzását/függő behúzást. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Visszaad az alapértelmezett tabulátor méretét. |
| [getTabs()](#getTabs--) | Visszaad egy bekezdés tabulációit. |
| [getFontAlignment()](#getFontAlignment--) | Visszaad a betűtípus igazítását egy bekezdésben. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Visszaad egy bekezdés alapértelmezett részformátumát. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Visszaad egy bekezdés felsorolásformátumát. Csak olvasható [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Visszatér:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Visszaad egy bekezdés mélységét. Csak olvasható short.

**Visszatér:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Visszaad a szöveg igazítását egy bekezdésben. Csak olvasható [TextAlignment](../../com.aspose.slides/textalignment).

**Visszatér:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Visszaad a sorok közötti távolságot egy bekezdésben. Csak olvasható float.

**Visszatér:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Visszaad a térközt az első sor előtt egy bekezdésben. Csak olvasható float.

**Visszatér:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Visszaad a térközt az utolsó sor után egy bekezdésben. Csak olvasható float.

**Visszatér:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Megállapítja, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Csak olvasható boolean.

**Visszatér:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Megállapítja, hogy jobbról balra írás irányt használják-e egy bekezdésben. Csak olvasható boolean.

**Visszatér:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Megállapítja, hogy a latin sortörést használják-e egy bekezdésben. Csak olvasható boolean.

**Visszatér:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Megállapítja, hogy függő írásjelet használnak-e egy bekezdésben. Csak olvasható boolean.

**Visszatér:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Visszaad a bal margót egy bekezdésben. Csak olvasható float.

**Visszatér:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Visszaad a jobb margót egy bekezdésben. Csak olvasható float.

**Visszatér:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Visszaad a bekezdés első sor behúzását/függő behúzást. A függő behúzás negatív értékekkel is definiálható. Csak olvasható float.

**Visszatér:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Visszaad az alapértelmezett tabulátor méretét. Csak olvasható float.

**Visszatér:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Visszaad egy bekezdés tabulációit. Csak olvasható ITabEffectiveData[].

**Visszatér:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Visszaad a betűtípus igazítását egy bekezdésben. Csak olvasható [FontAlignment](../../com.aspose.slides/fontalignment).

**Visszatér:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Visszaad egy bekezdés alapértelmezett részformátumát. Csak olvasható [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Visszatér:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)