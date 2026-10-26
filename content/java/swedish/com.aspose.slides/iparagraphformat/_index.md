---
title: IParagraphFormat
second_title: Aspose.Slides for Java API-referens
description: Denna klass innehåller paragrafformateringsegenskaperna.
type: docs
url: /sv/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Denna klass innehåller paragrafformateringsegenskaperna. Till skillnad från [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera paragrafformateringsegenskaper som definierats för den specifika paragrafen. Detta betyder att ingen arv tillämpas när värden hämtas så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective)-metoden som returnerar en [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBullet()](#getBullet--) | Returns bullet format of the paragraph. |
| [getDepth()](#getDepth--) | Returns or sets depth of the paragraph. |
| [setDepth(short value)](#setDepth-short-) | Returns or sets depth of the paragraph. |
| [getAlignment()](#getAlignment--) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [getSpaceWithin()](#getSpaceWithin--) | Returns or sets the amount of space between base lines in a paragraph. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returns or sets the amount of space between base lines in a paragraph. |
| [getSpaceBefore()](#getSpaceBefore--) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [getSpaceAfter()](#getSpaceAfter--) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determines whether the East Asian line break is used in a paragraph. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determines whether the East Asian line break is used in a paragraph. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the Right to Left writing is used in a paragraph. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determines whether the Right to Left writing is used in a paragraph. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determines whether the Latin line break is used in a paragraph. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determines whether the Latin line break is used in a paragraph. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determines whether the hanging punctuation is used in a paragraph. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determines whether the hanging punctuation is used in a paragraph. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin in a paragraph with no inheritance. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returns or sets the left margin in a paragraph with no inheritance. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin in a paragraph with no inheritance. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returns or sets the right margin in a paragraph with no inheritance. |
| [getIndent()](#getIndent--) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [setIndent(float value)](#setIndent-float-) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returns or sets default tabulation size with no inheritance. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returns or sets default tabulation size with no inheritance. |
| [getTabs()](#getTabs--) | Returns tabulations of a paragraph. |
| [getFontAlignment()](#getFontAlignment--) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returns default portion format of a paragraph. |
| [getEffective()](#getEffective--) | Gets effective paragraph formatting data with the inheritance applied. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Returnerar punktformat för paragrafen. Skrivskyddad [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Returnerar:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Returnerar eller anger djupet för paragrafen. Värde 0 betyder odefinierat värde. Läs/skriv short.

**Returnerar:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Returnerar eller anger djupet för paragrafen. Värde 0 betyder odefinierat värde. Läs/skriv short.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Returnerar eller anger textjusteringen i en paragraf utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

**Returnerar:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Returnerar eller anger textjusteringen i en paragraf utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Returnerar eller anger mängden utrymme mellan baskurvor i en paragraf. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv float.

**Returnerar:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Returnerar eller anger mängden utrymme mellan baskurvor i en paragraf. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Returnerar eller anger mängden utrymme före den första raden i en paragraf utan arv. Ett positivt värde anger procentsatsen av teckenstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Returnerar:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Returnerar eller anger mängden utrymme före den första raden i en paragraf utan arv. Ett positivt värde anger procentsatsen av teckenstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Returnerar eller anger mängden utrymme efter den sista raden i en paragraf utan arv. Ett positivt värde anger procentsatsen av teckenstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Returnerar:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Returnerar eller anger mängden utrymme efter den sista raden i en paragraf utan arv. Ett positivt värde anger procentsatsen av teckenstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Avgör om radbrytning för östasiatiskt skriftsystem används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Avgör om radbrytning för östasiatiskt skriftsystem används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Avgör om höger-till-vänster-skrivning används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Avgör om höger-till-vänster-skrivning används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Avgör om radbrytning för latinska tecken används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Avgör om radbrytning för latinska tecken används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Avgör om hängande interpunktion används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Avgör om hängande interpunktion används i en paragraf. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Returnerar eller anger vänstermarginalen i en paragraf utan arv. Läs/skriv float.

**Returnerar:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Returnerar eller anger vänstermarginalen i en paragraf utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Returnerar eller anger högermarginalen i en paragraf utan arv. Läs/skriv float.

**Returnerar:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Returnerar eller anger högermarginalen i en paragraf utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Returnerar eller anger första radindragning/hängande indragning i en paragraf utan arv. Hängande indragning kan definieras med negativa värden. Läs/skriv float.

**Returnerar:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Returnerar eller anger första radindragning/hängande indragning i en paragraf utan arv. Hängande indragning kan definieras med negativa värden. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Returnerar eller anger standardtabbstorlek utan arv. Läs/skriv float.

**Returnerar:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Returnerar eller anger standardtabbstorlek utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Returnerar tabbstopp för en paragraf. Ingen arv tillämpas. Skrivskyddad [ITabCollection](../../com.aspose.slides/itabcollection).

**Returnerar:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Returnerar eller anger teckenjustering i en paragraf utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Returnerar:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Returnerar eller anger teckenjustering i en paragraf utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Returnerar standarddelformat för en paragraf. Ingen arv tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Hämtar effektiv paragrafformateringsdata med arv tillämpat.

**Returnerar:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).