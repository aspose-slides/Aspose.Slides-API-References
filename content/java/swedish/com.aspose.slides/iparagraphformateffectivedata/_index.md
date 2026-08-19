---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /sv/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva styckeformateringsegenskaper.

--------------------

Detta gränssnitt används tillsammans med [IParagraphFormat](../../com.aspose.slides/iparagraphformat)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBullet()](#getBullet--) | Returnerar ett punktformat för ett stycke. |
| [getDepth()](#getDepth--) | Returnerar djupet för ett stycke. |
| [getAlignment()](#getAlignment--) | Returnerar textjusteringen i ett stycke. |
| [getSpaceWithin()](#getSpaceWithin--) | Returnerar mängden utrymme mellan baslinjer i ett stycke. |
| [getSpaceBefore()](#getSpaceBefore--) | Returnerar mängden utrymme före den första raden i ett stycke. |
| [getSpaceAfter()](#getSpaceAfter--) | Returnerar mängden utrymme efter den sista raden i ett stycke. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Fastställer om East Asian-radbrytning används i ett stycke. |
| [getRightToLeft()](#getRightToLeft--) | Fastställer om Right to Left-skrivning används i ett stycke. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Fastställer om Latin-radbrytning används i ett stycke. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Fastställer om hängande interpunktion används i ett stycke. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar vänstermarginalen i ett stycke. |
| [getMarginRight()](#getMarginRight--) | Returnerar högermarginalen i ett stycke. |
| [getIndent()](#getIndent--) | Returnerar styckets första radindrag/hängande indrag. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returnerar standardtabbstorlek. |
| [getTabs()](#getTabs--) | Returnerar tabulatorer för ett stycke. |
| [getFontAlignment()](#getFontAlignment--) | Returnerar en teckensnittsjustering i ett stycke. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returnerar standarddelformat för ett stycke. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Returnerar ett punktformat för ett stycke. Skrivskyddad [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returnerar:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Returnerar djupet för ett stycke. Skrivskyddad short.

**Returnerar:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returnerar textjusteringen i ett stycke. Skrivskyddad [TextAlignment](../../com.aspose.slides/textalignment).

**Returnerar:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Returnerar mängden utrymme mellan baslinjer i ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Returnerar mängden utrymme före den första raden i ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Returnerar mängden utrymme efter den sista raden i ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Fastställer om East Asian-radbrytning används i ett stycke. Skrivskyddad boolean.

**Returnerar:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Fastställer om Right to Left-skrivning används i ett stycke. Skrivskyddad boolean.

**Returnerar:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Fastställer om Latin-radbrytning används i ett stycke. Skrivskyddad boolean.

**Returnerar:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Fastställer om hängande interpunktion används i ett stycke. Skrivskyddad boolean.

**Returnerar:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Returnerar vänstermarginalen i ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Returnerar högermarginalen i ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Returnerar styckets första radindrag/hängande indrag. Hängande indrag kan definieras med negativa värden. Skrivskyddad float.

**Returnerar:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Returnerar standardtabbstorlek. Skrivskyddad float.

**Returnerar:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Returnerar tabulatorer för ett stycke. Skrivskyddad ITabEffectiveData[].

**Returnerar:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Returnerar en teckensnittsjustering i ett stycke. Skrivskyddad [FontAlignment](../../com.aspose.slides/fontalignment).

**Returnerar:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Returnerar standarddelformat för ett stycke. Skrivskyddad [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returnerar:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)