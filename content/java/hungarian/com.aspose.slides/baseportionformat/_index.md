---
title: BasePortionFormat
second_title: Aspose.Slides Java API referencia
description: Közös szövegrész formázási tulajdonságok.
type: docs
url: /hu/com.aspose.slides/baseportionformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Közös szövegrész formázási tulajdonságok.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveg kiemeléséhez használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja a aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Megállapítja, hogy a betűtípus félkövér-e. |
| [setFontBold(byte value)](#setFontBold-byte-) | Megállapítja, hogy a betűtípus félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Megállapítja, hogy a betűtípus dőlt-e. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Megállapítja, hogy a betűtípus dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. |
| [getProofDisabled()](#getProofDisabled--) | Megállapítja, hogy a szöveget ne kell-e helyesírásellenőrizni. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Megállapítja, hogy a szöveget ne kell-e helyesírásellenőrizni. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja vagy beállítja a szöveg nagybetűs formátumának típusát. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Visszaadja vagy beállítja a szöveg nagybetűs formátumának típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja vagy beállítja a szöveg áthúzás típusát. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Visszaadja vagy beállítja a szöveg áthúzás típusát. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [getFontHeight()](#getFontHeight--) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [setFontHeight(float value)](#setFontHeight-float-) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a latin betűtípus információt. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a latin betűtípus információt. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja vagy beállítja a szimbolikus betűtípus információt. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a szimbolikus betűtípus információt. |
| [getEscapement()](#getEscapement--) | Visszaadja vagy beállítja a felső- vagy alsó index szöveget. |
| [setEscapement(float value)](#setEscapement-float-) | Visszaadja vagy beállítja a felső- vagy alsó index szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja vagy beállítja a minimális betűméretet, amelyhez a kerninget be kell kapcsolni. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Visszaadja vagy beállítja a minimális betűméretet, amelyhez a kerninget be kell kapcsolni. |
| [getLanguageId()](#getLanguageId--) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja vagy beállítja a karakterek közötti távolság növekedését. |
| [setSpacing(float value)](#setSpacing-float-) | Visszaadja vagy beállítja a karakterek közötti távolság növekedését. |
| [getSpellCheck()](#getSpellCheck--) | Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés alkalmazva. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Megállapítja, hogy a szöveget ne kell-e helyesírásellenőrizni. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Megállapítja, hogy a szöveget ne kell-e helyesírásellenőrizni. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatér:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Visszaadja vagy beállítja a szöveg nagybetűs formátumának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatér:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Visszaadja vagy beállítja a szöveg nagybetűs formátumának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextCapType](../../com.aspose.slides/textcaptype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Visszaadja vagy beállítja a szöveg áthúzás típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatér:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Visszaadja vagy beállítja a szöveg áthúzás típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Visszatér:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Visszaadja vagy beállítja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Visszaadja vagy beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Visszaadja vagy beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Visszaadja vagy beállítja a felső- vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Visszatér:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Visszaadja vagy beállítja a felső- vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Visszaadja vagy beállítja a minimális betűméretet, amelyhez a kerninget be kell kapcsolni. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Visszatér:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Visszaadja vagy beállítja a minimális betűméretet, amelyhez a kerninget be kell kapcsolni. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtan-ellenőrzéshez használatos. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtan-ellenőrzéshez használatos. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Visszaadja vagy beállítja a karakterek közötti távolság növekedését. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Visszatér:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Visszaadja vagy beállítja a karakterek közötti távolság növekedését. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mastertől kell örökölni. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a false .

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Hozzáférés az első dia első alakzatának első szövegrészéhez
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Engedélyezi a helyesírás-ellenőrzést ennek a szövegrésszel
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentés a módosított bemutatóval
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose(); // Felszabadít
>  }
> ```


**Visszatér:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a false .

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Hozzáférés az első dia első alakzatának első szövegrészéhez
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Engedélyezi a helyesírás-ellenőrzést ennek a szövegrésznek
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentés a módosított prezentációval
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |