---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API referenciája
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-től eltérően ennek az osztálynak az összes tulajdonsága írható.

Ez az osztály a meghatározott szövegrészhez definiált szövegrész formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazul öröklődés, így a legtöbb esetben „nem definiált” értékeket kap.

A hatékony, az öröklődést is tartalmazó formázási paraméterértékek lekéréséhez a [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust kell használni, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveget kiemeléshez használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Megállapítja, hogy a betűtípus félkövér-e. |
| [setFontBold(byte value)](#setFontBold-byte-) | Megállapítja, hogy a betűtípus félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Megállapítja, hogy a betűtípus dőlt-e. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Megállapítja, hogy a betűtípus dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a keleti nyelvre jellemző függőleges szövegelrendezést. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a keleti nyelvre jellemző függőleges szövegelrendezést. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Megállapítja, hogy a szöveg magassága normalizálandó-e. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Megállapítja, hogy a szöveg magassága normalizálandó-e. |
| [getProofDisabled()](#getProofDisabled--) | Megállapítja, hogy a szöveg ne legyen lektorálva. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Megállapítja, hogy a szöveg ne legyen lektorálva. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja vagy beállítja a szöveg nagybetűs írási típusát. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Visszaadja vagy beállítja a szöveg nagybetűs írási típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja vagy beállítja a szöveg áthúzási típusát. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Visszaadja vagy beállítja a szöveg áthúzási típusát. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [getFontHeight()](#getFontHeight--) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [setFontHeight(float value)](#setFontHeight-float-) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a Latin betűtípus információkat. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Latin betűtípus információkat. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információkat. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információkat. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információkat. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információkat. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja vagy beállítja a szimbolikus betűtípus információkat. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a szimbolikus betűtípus információkat. |
| [getEscapement()](#getEscapement--) | Visszaadja vagy beállítja a felső vagy alsó index szöveget. |
| [setEscapement(float value)](#setEscapement-float-) | Visszaadja vagy beállítja a felső vagy alsó index szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolnia. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolnia. |
| [getLanguageId()](#getLanguageId--) | Visszaadja vagy beállítja egy lektoráló nyelv azonosítóját. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy lektoráló nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja vagy beállítja a karakterek közötti távolság növelését. |
| [setSpacing(float value)](#setSpacing-float-) | Visszaadja vagy beállítja a karakterek közötti távolság növelését. |
| [getSpellCheck()](#getSpellCheck--) | Megadja vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrész számára. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Megadja vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrész számára. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Visszaadja a szöveget kiemeléshez használt színt. Nincs öröklődés alkalmazva. **Csak olvasható** [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a keleti nyelvre jellemző függőleges szövegelrendezést. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a keleti nyelvre jellemző függőleges szövegelrendezést. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Megállapítja, hogy a szöveg magassága normalizálandó-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Megállapítja, hogy a szöveg magassága normalizálandó-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Megállapítja, hogy a szöveg ne legyen lektorálva. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Megállapítja, hogy a szöveg ne legyen lektorálva. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatér:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Visszaadja vagy beállítja a szöveg nagybetűs írási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatér:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Visszaadja vagy beállítja a szöveg nagybetűs írási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextCapType](../../com.aspose.slides/textcaptype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatér:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Visszatér:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Visszaadja vagy beállítja a Latin betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a Latin betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Visszaadja vagy beállítja a szimbolikus betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Visszaadja vagy beállítja a szimbolikus betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Visszaadja vagy beállítja a felső vagy alsó index szöveget. Az érték -100 % (alsó index) és 100 % (felső index) között van. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Visszatér:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Visszaadja vagy beállítja a felső vagy alsó index szöveget. Az érték -100 % (alsó index) és 100 % (felső index) között van. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolnia. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Visszatér:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolnia. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Visszaadja vagy beállítja egy lektoráló nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használatos. **Olvasás/írás** String.

**Visszatér:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Visszaadja vagy beállítja egy lektoráló nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használatos. **Olvasás/írás** String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. **Olvasás/írás** String.

**Visszatér:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. **Olvasás/írás** String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Visszaadja vagy beállítja a karakterek közötti távolság növelését. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Visszatér:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Visszaadja vagy beállítja a karakterek közötti távolság növelését. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. **Olvasás/írás** float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Megadja vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrész számára. Ha ez a tulajdonság false értékre van beállítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true értékre van beállítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Az első dián az első alakzatban lévő szövegrész első részének elérése
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // A helyesírás-ellenőrzés engedélyezése ehhez a szövegrészhez
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentse a módosított prezentációt
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Megadja vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrész számára. Ha ez a tulajdonság false értékre van beállítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true értékre van beállítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Az első dián az első alakzatban lévő szöveg első részének elérése
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // A helyesírás-ellenőrzés engedélyezése ehhez a szövegrészhez
>      portion.getPortionFormat().setSpellCheck(true);
>      // A módosított prezentáció mentése
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |