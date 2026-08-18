---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /hu/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Alap interfész a változtathatatlan objektumokhoz, amelyek hatékony szövegrész formázási tulajdonságokat tartalmaznak.
## Metódusok

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveget kiemeléshez használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Megállapítja, hogy a betűkészlet félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Megállapítja, hogy a betűkészlet dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Megállapítja, hogy a szöveg magassága normalizálandó-e. |
| [getProofDisabled()](#getProofDisabled--) | Megállapítja, hogy a szöveget ne kell-e ellenőrizni. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja a szöveg aláhúzási típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja a szöveg nagybetűs formázásának típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja a szöveg áthúzási típusát. |
| [getSmartTagClean()](#getSmartTagClean--) | Megállapítja, hogy a smart tag-et tisztítani kell-e. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Megállapítja, hogy az aláhúzási stílus rendelkezik-e saját LineFormat tulajdonságokkal, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Megállapítja, hogy az aláhúzási stílus rendelkezik-e saját FillFormat tulajdonságokkal, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. |
| [getFontHeight()](#getFontHeight--) | Visszaadja a szövegrész betűmagasságát pontban. |
| [getLatinFont()](#getLatinFont--) | Visszaadja a latin betűkészlet információkat. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja az kelet-ázsiai betűkészlet információkat. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja a komplex script betűkészlet információkat. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja a szimbolikus betűkészlet információkat. |
| [getEscapement()](#getEscapement--) | Visszaadja a felső vagy alsó index szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. |
| [getLanguageId()](#getLanguageId--) | Visszaadja egy nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja a karakterek közötti távolság növekedését pontban. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Csak olvasható [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Visszatér:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Visszaadja a szöveg FillFormat tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Visszatér:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Visszaadja a szöveg EffectFormat tulajdonságait. Csak olvasható [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Visszatér:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Visszaadja a szöveget kiemeléshez használt színt. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Csak olvasható [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Visszatér:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Visszatér:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Megállapítja, hogy a betűkészlet félkövér-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Megállapítja, hogy a betűkészlet dőlt-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Csak olvasható boolean.

**Visszatér:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Megállapítja, hogy a szöveg magassága normalizálandó-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Megállapítja, hogy a szöveget ne kell-e ellenőrizni. Csak olvasható boolean.

**Visszatér:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Visszaadja a szöveg aláhúzási típusát. Csak olvasható [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatér:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Visszaadja a szöveg nagybetűs formázásának típusát. Csak olvasható [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatér:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Visszaadja a szöveg áthúzási típusát. Csak olvasható [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatér:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Megállapítja, hogy a smart tag-et tisztítani kell-e. Csak olvasható boolean.

**Visszatér:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Megállapítja, hogy az aláhúzási stílus rendelkezik-e saját LineFormat tulajdonságokkal, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. Csak olvasható boolean.

**Visszatér:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Megállapítja, hogy az aláhúzási stílus rendelkezik-e saját FillFormat tulajdonságokkal, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. Csak olvasható boolean.

**Visszatér:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Visszaadja a szövegrész betűmagasságát pontban. Csak olvasható float.

**Visszatér:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Visszaadja a latin betűkészlet információkat. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Visszaadja az kelet-ázsiai betűkészlet információkat. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Visszaadja a komplex script betűkészlet információkat. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Visszaadja a szimbolikus betűkészlet információkat. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. Csak olvasható float.

**Visszatér:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. Csak olvasható float.

**Visszatér:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Visszaadja egy nyelv azonosítóját. Csak olvasható String.

**Visszatér:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Visszaadja egy alternatív nyelv azonosítóját. Csak olvasható String.

**Visszatér:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Visszaadja a karakterek közötti távolság növekedését pontban. Csak olvasható float.

**Visszatér:**
float