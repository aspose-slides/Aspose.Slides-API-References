---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /cs/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování odstavce.

--------------------

Toto rozhraní se používá spolu s rozhraním [IParagraphFormat](../../com.aspose.slides/iparagraphformat) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBullet()](#getBullet--) | Vrací formát odrážky odstavce. |
| [getDepth()](#getDepth--) | Vrací hloubku odstavce. |
| [getAlignment()](#getAlignment--) | Vrací zarovnání textu v odstavci. |
| [getSpaceWithin()](#getSpaceWithin--) | Vrací množství prostoru mezi základními řádky v odstavci. |
| [getSpaceBefore()](#getSpaceBefore--) | Vrací množství prostoru před první řádkou v odstavci. |
| [getSpaceAfter()](#getSpaceAfter--) | Vrací množství prostoru za poslední řádkou v odstavci. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Určuje, zda se v odstavci používá východoasijské zalomení řádku. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Určuje, zda se v odstavci používá zavěšená interpunkce. |
| [getMarginLeft()](#getMarginLeft--) | Vrací levý okraj v odstavci. |
| [getMarginRight()](#getMarginRight--) | Vrací pravý okraj v odstavci. |
| [getIndent()](#getIndent--) | Vrací odsazení prvního řádku / zavěšené odsazení odstavce. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Vrací výchozí velikost tabulátoru. |
| [getTabs()](#getTabs--) | Vrací tabulátory odstavce. |
| [getFontAlignment()](#getFontAlignment--) | Vrací zarovnání písma v odstavci. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Vrací výchozí formát úseku odstavce. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Vrací formát odrážky odstavce. Pouze pro čtení [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Vrací:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Vrací hloubku odstavce. Pouze pro čtení short.

**Vrací:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Vrací zarovnání textu v odstavci. Pouze pro čtení [TextAlignment](../../com.aspose.slides/textalignment).

**Vrací:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Vrací množství prostoru mezi základními řádky v odstavci. Pouze pro čtení float.

**Vrací:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Vrací množství prostoru před první řádkou v odstavci. Pouze pro čtení float.

**Vrací:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Vrací množství prostoru za poslední řádkou v odstavci. Pouze pro čtení float.

**Vrací:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Určuje, zda se v odstavci používá východoasijské zalomení řádku. Pouze pro čtení boolean.

**Vrací:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Určuje, zda se v odstavci používá zápis zprava doleva. Pouze pro čtení boolean.

**Vrací:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Určuje, zda se v odstavci používá latinské zalomení řádku. Pouze pro čtení boolean.

**Vrací:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Určuje, zda se v odstavci používá zavěšená interpunkce. Pouze pro čtení boolean.

**Vrací:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Vrací levý okraj v odstavci. Pouze pro čtení float.

**Vrací:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Vrací pravý okraj v odstavci. Pouze pro čtení float.

**Vrací:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Vrací odsazení prvního řádku / zavěšené odsazení odstavce. Zavěšené odsazení může být definováno zápornými hodnotami. Pouze pro čtení float.

**Vrací:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Vrací výchozí velikost tabulátoru. Pouze pro čtení float.

**Vrací:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Vrací tabulátory odstavce. Pouze pro čtení ITabEffectiveData[].

**Vrací:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Vrací zarovnání písma v odstavci. Pouze pro čtení [FontAlignment](../../com.aspose.slides/fontalignment).

**Vrací:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Vrací výchozí formát úseku odstavce. Pouze pro čtení [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Vrací:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)