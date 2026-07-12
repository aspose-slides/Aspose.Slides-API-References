---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Alap interfész a hatékony szövegrészek formázási tulajdonságait tartalmazó változtathatatlan objektumokhoz.
type: docs
url: /hu/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Alap interfész a hatékony szövegrészek formázási tulajdonságait tartalmazó változtathatatlan objektumokhoz.
## Metódusok

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a szöveg körvonalazásához használt LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveg kiemeléséhez használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Meghatározza, hogy a betűtípus félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Meghatározza, hogy a betűtípus dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Meghatározza, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges szövegelrendezését. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Meghatározza, hogy a szöveg magassága normalizálandó-e. |
| [getProofDisabled()](#getProofDisabled--) | Meghatározza, hogy a szöveget ne kelljen helyesírási ellenőrzésnek alávetni. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja a szöveg aláhúzási típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja a szöveg nagybetűs írás típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja a szöveg áthúzási típusát. |
| [getSmartTagClean()](#getSmartTagClean--) | Meghatározza, hogy az okos címke tisztítandó-e. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [getFontHeight()](#getFontHeight--) | Visszaadja a szövegrész betűmagasságát pontban. |
| [getLatinFont()](#getLatinFont--) | Visszaadja a Latin betűtípus információit. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja a kelet-ázsiai betűtípus információit. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja a komplex szkript betűtípus információit. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja a szimbolikus betűtípus információit. |
| [getEscapement()](#getEscapement--) | Visszaadja a felső- vagy alsó index szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja a minimális betűméretet, amelynél a karakterközök aktiválódnak. |
| [getLanguageId()](#getLanguageId--) | Visszaadja egy nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja a karakterek közötti távolságnövekedést pontban. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Visszaadja a szöveg körvonalazásához használt LineFormat tulajdonságokat. Csak olvasható [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Visszatérési érték:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Visszaadja a szöveg FillFormat tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Visszatérési érték:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Visszaadja a szöveg EffectFormat tulajdonságait. Csak olvasható [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Visszatérési érték:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


Visszaadja a szöveg kiemeléséhez használt színt. Csak olvasható java.lang.Integer.

**Visszatérési érték:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Csak olvasható [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Visszatérési érték:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Visszatérési érték:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Megállapítja, hogy a betűtípus félkövér-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Megállapítja, hogy a betűtípus dőlt-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges szövegelrendezését. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Megállapítja, hogy a szöveg magassága normalizálandó-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Megállapítja, hogy a szöveget ne kelljen helyesírási ellenőrzésnek alávetni. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Visszaadja a szöveg aláhúzási típusát. Csak olvasható [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatérési érték:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Visszaadja a szöveg nagybetűs írás típusát. Csak olvasható [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatérési érték:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Visszaadja a szöveg áthúzási típusát. Csak olvasható [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatérési érték:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Megállapítja, hogy az okos címke tisztítandó-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Visszaadja a szövegrész betűmagasságát pontban. Csak olvasható float.

**Visszatérési érték:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Visszaadja a Latin betűtípus információit. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Visszaadja a kelet-ázsiai betűtípus információit. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Visszaadja a komplex szkript betűtípus információit. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Visszaadja a szimbolikus betűtípus információit. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Visszaadja a felső- vagy alsó index szöveget. Érték -100% (alsó index) és 100% (felső index) között. Csak olvasható float.

**Visszatérési érték:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Visszaadja a minimális betűméretet, amelynél a karakterközök aktiválódnak. Csak olvasható float.

**Visszatérési érték:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Visszaadja egy nyelv azonosítóját. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Visszaadja egy alternatív nyelv azonosítóját. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Visszaadja a karakterek közötti távolságnövekedést pontban. Csak olvasható float.

**Visszatérési érték:**
float