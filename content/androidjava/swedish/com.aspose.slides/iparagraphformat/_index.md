---
title: IParagraphFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass innehåller styckeformateringsegenskaperna.
type: docs
url: /sv/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Denna klass innehåller styckeformateringsegenskaperna. Till skillnad från [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera styckeformateringsegenskaper som definierats för ett specifikt stycke. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective)-metoden som returnerar en [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instans.
## Metoder

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Returnerar punktformat för stycket. |
| [getDepth()](#getDepth--) | Returnerar eller anger djupet för stycket. |
| [setDepth(short value)](#setDepth-short-) | Returnerar eller anger djupet för stycket. |
| [getAlignment()](#getAlignment--) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [setAlignment(int value)](#setAlignment-int-) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [getSpaceWithin()](#getSpaceWithin--) | Returnerar eller anger mängden avstånd mellan baslinjer i ett stycke. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returnerar eller anger mängden avstånd mellan baslinjer i ett stycke. |
| [getSpaceBefore()](#getSpaceBefore--) | Returnerar eller anger mängden avstånd före den första raden i ett stycke utan arv. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returnerar eller anger mängden avstånd före den första raden i ett stycke utan arv. |
| [getSpaceAfter()](#getSpaceAfter--) | Returnerar eller anger mängden avstånd efter den sista raden i ett stycke utan arv. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returnerar eller anger mängden avstånd efter den sista raden i ett stycke utan arv. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Avgör om radbrytning för östasiatiska språk används i ett stycke. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Avgör om radbrytning för östasiatiska språk används i ett stycke. |
| [getRightToLeft()](#getRightToLeft--) | Avgör om högra-till-vänster-skrivning används i ett stycke. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Avgör om högra-till-vänster-skrivning används i ett stycke. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Avgör om latinsk radbrytning används i ett stycke. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Avgör om latinsk radbrytning används i ett stycke. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Avgör om hängande interpunktion används i ett stycke. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Avgör om hängande interpunktion används i ett stycke. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [getIndent()](#getIndent--) | Returnerar eller anger styckets första rad-indragning/hängande indrag utan arv. |
| [setIndent(float value)](#setIndent-float-) | Returnerar eller anger styckets första rad-indragning/hängande indrag utan arv. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returnerar eller anger standardtabuleringsstorlek utan arv. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returnerar eller anger standardtabuleringsstorlek utan arv. |
| [getTabs()](#getTabs--) | Returnerar tabulatorer för ett stycke. |
| [getFontAlignment()](#getFontAlignment--) | Returnerar eller anger teckensnittsjustering i ett stycke utan arv. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returnerar eller anger teckensnittsjustering i ett stycke utan arv. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returnerar standardportionformat för ett stycke. |
| [getEffective()](#getEffective--) | Hämtar effektiva styckeformateringsdata med arv tillämpat. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Returnerar punktformat för stycket. Skrivskyddad [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Returnerar:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Returnerar eller anger djupet för stycket. Värde 0 betyder odefinierat värde. Läs/skriv short.

**Returnerar:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Returnerar eller anger djupet för stycket. Värde 0 betyder odefinierat värde. Läs/skriv short.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

**Returnerar:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Returnerar eller anger mängden avstånd mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv float.

**Returnerar:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Returnerar eller anger mängden avstånd mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Returnerar eller anger mängden avstånd före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckenstorleken för det vita utrymmet. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Returnerar:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Returnerar eller anger mängden avstånd före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckenstorleken för det vita utrymmet. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Returnerar eller anger mängden avstånd efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckenstorleken för det vita utrymmet. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Returnerar:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Returnerar eller anger mängden avstånd efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckenstorleken för det vita utrymmet. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Avgör om radbrytning för östasiatiska språk används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Avgör om radbrytning för östasiatiska språk används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Avgör om högra-till-vänster-skrivning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Avgör om högra-till-vänster-skrivning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Avgör om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Avgör om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Avgör om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Avgör om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv float.

**Returnerar:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv float.

**Returnerar:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Returnerar eller anger styckets första rad-indragning/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv float.

**Returnerar:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Returnerar eller anger styckets första rad-indragning/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Returnerar eller anger standardtabuleringsstorlek utan arv. Läs/skriv float.

**Returnerar:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Returnerar eller anger standardtabuleringsstorlek utan arv. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Returnerar tabulatorer för ett stycke. Ingen arv tillämpas. Skrivskyddad [ITabCollection](../../com.aspose.slides/itabcollection).

**Returnerar:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Returnerar eller anger teckensnittsjustering i ett stycke utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Returnerar:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Returnerar eller anger teckensnittsjustering i ett stycke utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Returnerar standardportionformat för ett stycke. Ingen arv tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Hämtar effektiva styckeformateringsdata med arv tillämpat.

**Returnerar:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).