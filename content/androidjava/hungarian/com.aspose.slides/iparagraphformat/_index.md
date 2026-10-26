---
title: IParagraphFormat
second_title: Aspose.Slides for Android Java API-referencia
description: Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat.
type: docs
url: /hu/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-től eltérően az osztály összes tulajdonsága írható.

--------------------

Ez az osztály arra szolgál, hogy visszaadja és módosítsa a konkrét bekezdéshez definiált bekezdésformázási tulajdonságokat. Ez azt jelenti, hogy az értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket fog kapni, amelyek értelmezése „nem definiált”.  
A hatékony formázási paraméterértékek, így az örökölt értékek lekéréséhez a [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) módszert kell használni, amely egy [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) példányt ad vissza.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBullet()](#getBullet--) | Visszaadja a bekezdés felsorolásformátumát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [setDepth(short value)](#setDepth-short-) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a szöveg igazítást egy bekezdésben öröklődés nélkül. |
| [setAlignment(int value)](#setAlignment-int-) | Visszaadja vagy beállítja a szöveg igazítást egy bekezdésben öröklődés nélkül. |
| [getSpaceWithin()](#getSpaceWithin--) | Visszaadja vagy beállítja az alapvonalak közti távolságot egy bekezdésben. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Visszaadja vagy beállítja az alapvonalak közti távolságot egy bekezdésben. |
| [getSpaceBefore()](#getSpaceBefore--) | Visszaadja vagy beállítja az első sor előtti távolságot egy bekezdésben öröklődés nélkül. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Visszaadja vagy beállítja az első sor előtti távolságot egy bekezdésben öröklődés nélkül. |
| [getSpaceAfter()](#getSpaceAfter--) | Visszaadja vagy beállítja az utolsó sor utáni távolságot egy bekezdésben öröklődés nélkül. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Visszaadja vagy beállítja az utolsó sor utáni távolságot egy bekezdésben öröklődés nélkül. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. |
| [getRightToLeft()](#getRightToLeft--) | Meghatározza, hogy a jobbról balra írást használják-e egy bekezdésben. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Meghatározza, hogy a jobbról balra írást használják-e egy bekezdésben. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Meghatározza, hogy a függőleges írásjelet használják-e egy bekezdésben. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Meghatározza, hogy a függőleges írásjelet használják-e egy bekezdésben. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [setMarginRight(float value)](#setMarginRight-float-) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [getIndent()](#getIndent--) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függőleges behúzását öröklődés nélkül. |
| [setIndent(float value)](#setIndent-float-) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függőleges behúzását öröklődés nélkül. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Visszaadja vagy beállítja az alapértelmezett tabulátor méretet öröklődés nélkül. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Visszaadja vagy beállítja az alapértelmezett tabulátor méretet öröklődés nélkül. |
| [getTabs()](#getTabs--) | Visszaadja a bekezdés tabulátorait. |
| [getFontAlignment()](#getFontAlignment--) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Visszaadja a bekezdés alapértelmezett részformátumát. |
| [getEffective()](#getEffective--) | Megkapja a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Visszaadja a bekezdés felsorolásformátumát. Csak olvasható [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Visszatér:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték nem definiált értéket jelent. Olvasás/írás short.

**Visszatér:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték nem definiált értéket jelent. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Visszaadja vagy beállítja a szöveg igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

**Visszatér:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Visszaadja vagy beállítja a szöveg igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Visszaadja vagy beállítja az alapvonalak közti távolságot egy bekezdésben. Pozitív érték százalékot jelent, negatív – pontméretet. Nincs öröklődés. Olvasás/írás float.

**Visszatér:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Visszaadja vagy beállítja az alapvonalak közti távolságot egy bekezdésben. Pozitív érték százalékot jelent, negatív – pontméretet. Nincs öröklődés. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Visszaadja vagy beállítja az első sor előtti távolságot egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben adja meg a fehér területet. Olvasás/írás float.

**Visszatér:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Visszaadja vagy beállítja az első sor előtti távolságot egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben adja meg a fehér területet. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Visszaadja vagy beállítja az utolsó sor utáni távolságot egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben adja meg a fehér területet. Olvasás/írás float.

**Visszatér:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Visszaadja vagy beállítja az utolsó sor utáni távolságot egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben adja meg a fehér területet. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Meghatározza, hogy a jobbról balra írást használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Meghatározza, hogy a jobbról balra írást használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Meghatározza, hogy a függőleges írásjelet használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Meghatározza, hogy a függőleges írásjelet használják-e egy bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Visszaadja vagy beállítja a bekezdés első sor behúzását/függőleges behúzását öröklődés nélkül. A függőleges behúzás negatív értékkel definiálható. Olvasás/írás float.

**Visszatér:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Visszaadja vagy beállítja a bekezdés első sor behúzását/függőleges behúzását öröklődés nélkül. A függőleges behúzás negatív értékkel definiálható. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Visszaadja vagy beállítja az alapértelmezett tabulátor méretet öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Visszaadja vagy beállítja az alapértelmezett tabulátor méretet öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Visszaadja a bekezdés tabulátorait. Nincs öröklődés. Csak olvasható [ITabCollection](../../com.aspose.slides/itabcollection).

**Visszatér:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [FontAlignment](../../com.aspose.slides/fontalignment).

**Visszatér:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [FontAlignment](../../com.aspose.slides/fontalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Visszaadja a bekezdés alapértelmezett részformátumát. Nincs öröklődés. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Megkapja a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).