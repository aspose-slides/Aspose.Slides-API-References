---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onbewerkbaar object dat effectieve alinea-opmaak eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Onbewerkbaar object dat effectieve alinea-opmaak eigenschappen bevat.

--------------------

Deze interface wordt samen met de [IParagraphFormat](../../com.aspose.slides/iparagraphformat) interface gebruikt om effectieve opmaakwaarden met geërfde instellingen terug te geven.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBullet()](#getBullet--) | Retourneert een bullet-indeling van een alinea. |
| [getDepth()](#getDepth--) | Retourneert de diepte van een alinea. |
| [getAlignment()](#getAlignment--) | Retourneert de tekstuitlijning in een alinea. |
| [getSpaceWithin()](#getSpaceWithin--) | Retourneert de hoeveelheid ruimte tussen basislijnen in een alinea. |
| [getSpaceBefore()](#getSpaceBefore--) | Retourneert de hoeveelheid ruimte vóór de eerste regel in een alinea. |
| [getSpaceAfter()](#getSpaceAfter--) | Retourneert de hoeveelheid ruimte na de laatste regel in een alinea. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of het Latijnse regeleinde wordt gebruikt in een alinea. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert de linkermarge in een alinea. |
| [getMarginRight()](#getMarginRight--) | Retourneert de rechtermarge in een alinea. |
| [getIndent()](#getIndent--) | Retourneert alinea First Line Indent/Hanging Indent. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retourneert de standaard tabgrootte. |
| [getTabs()](#getTabs--) | Retourneert tabs van een alinea. |
| [getFontAlignment()](#getFontAlignment--) | Retourneert een lettertype-uitlijning in een alinea. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retourneert het standaardgedeelteformaat van een alinea. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Retourneert een bullet-indeling van een alinea. Alleen-lezen [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Retourneert de diepte van een alinea. Alleen-lezen short.

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Retourneert de tekstuitlijning in een alinea. Alleen-lezen [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Retourneert de hoeveelheid ruimte tussen basislijnen in een alinea. Alleen-lezen float.

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Retourneert de hoeveelheid ruimte vóór de eerste regel in een alinea. Alleen-lezen float.

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Retourneert de hoeveelheid ruimte na de laatste regel in een alinea. Alleen-lezen float.

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. Alleen-lezen boolean.

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Alleen-lezen boolean.

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Bepaalt of het Latijnse regeleinde wordt gebruikt in een alinea. Alleen-lezen boolean.

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Alleen-lezen boolean.

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Retourneert de linkermarge in een alinea. Alleen-lezen float.

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Retourneert de rechtermarge in een alinea. Alleen-lezen float.

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Retourneert alinea First Line Indent/Hanging Indent. Hanging Indent kan worden gedefinieerd met negatieve waarden. Alleen-lezen float.

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Retourneert de standaard tabgrootte. Alleen-lezen float.

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Retourneert tabs van een alinea. Alleen-lezen ITabEffectiveData[].

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Retourneert een lettertype-uitlijning in een alinea. Alleen-lezen [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Retourneert het standaardgedeelteformaat van een alinea. Alleen-lezen [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)