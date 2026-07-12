---
title: BasePortionFormat
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
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

A szövegrész formázási tulajdonságainak általános részletei.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Visszaadja a körvonalazott szöveghez tartozó LineFormat tulajdonságokat. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a szöveg FillFormat tulajdonságait. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja a szöveg EffectFormat tulajdonságait. |
| [getHighlightColor()](#getHighlightColor--) | Visszaadja a szöveget kiemelésre használt színt. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Visszaadja az aláhúzó vonal körvonalazásához használt LineFormat tulajdonságokat. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Visszaadja az aláhúzó vonal FillFormat tulajdonságait. |
| [getFontBold()](#getFontBold--) | Megállapítja, hogy a betűtípus félkövér-e. |
| [setFontBold(byte value)](#setFontBold-byte-) | Megállapítja, hogy a betűtípus félkövér-e. |
| [getFontItalic()](#getFontItalic--) | Megállapítja, hogy a betűtípus dőlt-e. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Megállapítja, hogy a betűtípus dőlt-e. |
| [getKumimoji()](#getKumimoji--) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. |
| [getProofDisabled()](#getProofDisabled--) | Megállapítja, hogy a szöveget ne kell-e helyesírási ellenőrzésnek alávetni. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Megállapítja, hogy a szöveget ne kell-e helyesírási ellenőrzésnek alávetni. |
| [getFontUnderline()](#getFontUnderline--) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Visszaadja vagy beállítja a szöveg aláhúzási típusát. |
| [getTextCapType()](#getTextCapType--) | Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. |
| [getStrikethroughType()](#getStrikethroughType--) | Visszaadja vagy beállítja a szöveg áthúzási típusát. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Visszaadja vagy beállítja a szöveg áthúzási típusát. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. |
| [getFontHeight()](#getFontHeight--) | Visszaadja vagy beállítja egy rész betűméretét. |
| [setFontHeight(float value)](#setFontHeight-float-) | Visszaadja vagy beállítja egy rész betűméretét. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a latin betűtípus információit. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a latin betűtípus információit. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információit. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információit. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex szkript betűtípus információit. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex szkript betűtípus információit. |
| [getSymbolFont()](#getSymbolFont--) | Visszaadja vagy beállítja a szimbolikus betűtípus információit. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a szimbolikus betűtípus információit. |
| [getEscapement()](#getEscapement--) | Visszaadja vagy beállítja a felső- vagy alsóindex szöveget. |
| [setEscapement(float value)](#setEscapement-float-) | Visszaadja vagy beállítja a felső- vagy alsóindex szöveget. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. |
| [getLanguageId()](#getLanguageId--) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. |
| [getSpacing()](#getSpacing--) | Visszaadja vagy beállítja a karakterközi távolság növekedését. |
| [setSpacing(float value)](#setSpacing-float-) | Visszaadja vagy beállítja a karakterközi távolság növekedését. |
| [getSpellCheck()](#getSpellCheck--) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. |

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

Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Visszaadja a szöveget kiemelésre használt színt. Nincs öröklődés alkalmazva. **Csak olvasható** [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Visszaadja az aláhúzó vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Visszaadja az aláhúzó vonal FillFormat tulajdonságait. Nincs öröklődés alkalmazva. **Csak olvasható** [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Megállapítja, hogy a szöveget ne kell-e helyesírási ellenőrzésnek alávetni. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Megállapítja, hogy a szöveget ne kell-e helyesírási ellenőrzésnek alávetni. Nincs öröklődés alkalmazva. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Visszatér:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextCapType](../../com.aspose.slides/textcaptype).

**Visszatér:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextCapType](../../com.aspose.slides/textcaptype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Visszatér:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. **Olvasás/írás** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Visszaadja vagy beállítja a betűmagasságot egy részhez. **Float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Visszatér:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Visszaadja vagy beállítja a betűmagasságot egy részhez. **Float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Visszaadja vagy beállítja a latin betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a latin betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex szkript betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex szkript betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Visszaadja vagy beállítja a szimbolikus betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Visszaadja vagy beállítja a szimbolikus betűtípus információit. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Master-től öröklődik. **Olvasás/írás** [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Visszaadja vagy beállítja a felső- vagy alsóindex szöveget. Az érték –100 % (alsóindex) és 100 % (felsőindex) között lehet. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Visszatér:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Visszaadja vagy beállítja a felső- vagy alsóindex szöveget. Az érték –100 % (alsóindex) és 100 % (felsőindex) között lehet. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Visszatér:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtan-ellenőrzéshez használják. **Olvasás/írás** String.

**Visszatér:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtan-ellenőrzéshez használják. **Olvasás/írás** String.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. **Olvasás/írás** String.

**Visszatér:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. **Olvasás/írás** String.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Visszaadja vagy beállítja a karakterközi távolság növekedését. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Visszatér:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Visszaadja vagy beállítja a karakterközi távolság növekedését. **Float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Master-től öröklődik. **Olvasás/írás**  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság false-ra van állítva, a helyesírás-ellenőrzés a szövegelemekre nem vonatkozik. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték: false.

**Visszatér:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság false-ra van állítva, a helyesírás-ellenőrzés a szövegelemekre nem vonatkozik. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték: false.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Az első dián az első alakzat első szövegrészéhez való hozzáférés
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Engedélyezi a helyesírás-ellenőrzést ehhez a szövegrészhez
>      portion.getPortionFormat().setSpellCheck(true);
>      // Mentse a módosított bemutatót
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |