---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Ez a osztály a szövegrész formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

--------------------

Ez az osztály a konkrét részhez definiált szövegrész formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értékek lekérésekor nincs öröklődés alkalmazva, így a legtöbb esetben "undefined" értékű eredményeket kap.

A hatékony formázási paraméterértékek, beleértve az örökölt értékeket, megszerzéséhez a [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust kell használni, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveg kiemeléséhez használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Meghatározza, hogy a betűtípus félkövér-e. |
| [setFontBold(byte value)](#setFontBold-byte-) | Meghatározza, hogy a betűtípus félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Meghatározza, hogy a betűtípus dőlt-e. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Meghatározza, hogy a betűtípus dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Meghatározza, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvre jellemző függőleges szövegelrendezést. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Meghatározza, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvre jellemző függőleges szövegelrendezést. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Meghatározza, hogy a szöveg magassága normalizálva legyen-e. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Meghatározza, hogy a szöveg magassága normalizálva legyen-e. |
| [getProofDisabled()](#getProofDisabled--) | Meghatározza, hogy a szöveget ne ellenőrizzék. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Meghatározza, hogy a szöveget ne ellenőrizzék. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja vagy beállítja a szöveg aláhúzás típusát. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Visszaadja vagy beállítja a szöveg aláhúzás típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja vagy beállítja a szöveg nagybetűs írásának típusát. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Visszaadja vagy beállítja a szöveg nagybetűs írásának típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja vagy beállítja a szöveg áthúzásának típusát. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Visszaadja vagy beállítja a szöveg áthúzásának típusát. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. |
| [getFontHeight()](#getFontHeight--) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [setFontHeight(float value)](#setFontHeight-float-) | Visszaadja vagy beállítja egy rész betűmagasságát. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a Latin betűtípus információt. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Latin betűtípus információt. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a Kelet-Ázsiai betűtípus információt. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Kelet-Ázsiai betűtípus információt. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex szkript betűtípus információt. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex szkript betűtípus információt. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja vagy beállítja a szimbolikus betűtípus információt. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a szimbolikus betűtípus információt. |
| [getEscapement()](#getEscapement--) | Visszaadja vagy beállítja a felső vagy alsó index szöveget. |
| [setEscapement(float value)](#setEscapement-float-) | Visszaadja vagy beállítja a felső vagy alsó index szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kellene kapcsolódnia. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kellene kapcsolódnia. |
| [getLanguageId()](#getLanguageId--) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja vagy beállítja a karakterek közötti távolság növekedését. |
| [setSpacing(float value)](#setSpacing-float-) | Visszaadja vagy beállítja a karakterek közötti távolság növekedését. |
| [getSpellCheck()](#getSpellCheck--) | Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés alkalmazva. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Meghatározza, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Meghatározza, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Meghatározza, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Meghatározza, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Meghatározza, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvre jellemző függőleges szövegelrendezést. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Meghatározza, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvre jellemző függőleges szövegelrendezést. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Meghatározza, hogy a szöveg magassága normalizálva legyen-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Meghatározza, hogy a szöveg magassága normalizálva legyen-e. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Meghatározza, hogy a szöveget ne ellenőrizzék. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Meghatározza, hogy a szöveget ne ellenőrizzék. Nincs öröklődés alkalmazva. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatér:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Visszaadja vagy beállítja a szöveg nagybetűs írásának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatér:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Visszaadja vagy beállítja a szöveg nagybetűs írásának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextCapType](../../com.aspose.slides/textcaptype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Visszaadja vagy beállítja a szöveg áthúzásának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatér:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Visszaadja vagy beállítja a szöveg áthúzásának típusát. Nincs öröklődés alkalmazva. Olvasás/írás [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Visszatér:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Visszaadja vagy beállítja egy rész betűmagasságát. **Float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Visszaadja vagy beállítja a Latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a Latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a Kelet-Ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a Kelet-Ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex szkript betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex szkript betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Visszaadja vagy beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Visszaadja vagy beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Visszaadja vagy beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között lehet. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Visszatér:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Visszaadja vagy beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között lehet. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kellene kapcsolódnia. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Visszatér:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kellene kapcsolódnia. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtani ellenőrzésre használható. Olvasás/írás String.

**Visszatér:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtani ellenőrzésre használható. Olvasás/írás String.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String.

**Visszatér:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Visszaadja vagy beállítja a karakterek közötti távolság növekményét. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Visszatér:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Visszaadja vagy beállítja a karakterek közötti távolság növekményét. **Float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a mesterből kell örökölni. Olvasás/írás float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true értékre van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Hozzáférés az első szövegrészhez az első dián lévő első alakzatban
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Engedélyezi a helyesírás-ellenőrzést ehhez a szövegrészhez
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentse el a módosított prezentációt
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

Lekéri vagy beállítja, hogy a szövegrészhez engedélyezve van-e a helyesírás-ellenőrzés. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true értékre van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Hozzáférés az első szövegrészhez az első dián lévő első alakzatban
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Engedélyezi a helyesírás-ellenőrzést ehhez a szövegrészhez
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentse el a módosított prezentációt
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |