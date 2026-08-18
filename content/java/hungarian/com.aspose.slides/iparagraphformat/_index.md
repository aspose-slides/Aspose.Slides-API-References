---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: Ez az osztály tartalmazza a bekezdés formázási tulajdonságait.
type: docs
url: /hu/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-tól eltérően, az osztály összes tulajdonsága írható.

--------------------

Ez az osztály a konkrét bekezdéshez definiált bekezdés formázási tulajdonságok lekérésére és módosítására szolgál. Ez azt jelenti, hogy értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben "undefined" értékeket kap.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterértékek lekéréséhez a [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) metódust kell használni, amely egy [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) példányt ad vissza.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getBullet()](#getBullet--) | Visszaadja a bekezdés bullet formátumát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [setDepth(short value)](#setDepth-short-) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül. |
| [setAlignment(int value)](#setAlignment-int-) | Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül. |
| [getSpaceWithin()](#getSpaceWithin--) | Visszaadja vagy beállítja a sorok közötti távolságot egy bekezdésben. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Visszaadja vagy beállítja a sorok közötti távolságot egy bekezdésben. |
| [getSpaceBefore()](#getSpaceBefore--) | Visszaadja vagy beállítja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Visszaadja vagy beállítja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. |
| [getSpaceAfter()](#getSpaceAfter--) | Visszaadja vagy beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Visszaadja vagy beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Meghatározza, hogy a kelet-ázsiai sortörés használatos-e egy bekezdésben. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Meghatározza, hogy a kelet-ázsiai sortörés használatos-e egy bekezdésben. |
| [getRightToLeft()](#getRightToLeft--) | Meghatározza, hogy a jobbról balra írás használatos-e egy bekezdésben. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Meghatározza, hogy a jobbról balra írás használatos-e egy bekezdésben. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Meghatározza, hogy a latin sortörés használatos-e egy bekezdésben. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Meghatározza, hogy a latin sortörés használatos-e egy bekezdésben. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Meghatározza, hogy a függőleges központozás használatos-e egy bekezdésben. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Meghatározza, hogy a függőleges központozás használatos-e egy bekezdésben. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [setMarginRight(float value)](#setMarginRight-float-) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [getIndent()](#getIndent--) | Visszaadja vagy beállítja az első sor behúzást/függőleges behúzást egy bekezdésben öröklődés nélkül. |
| [setIndent(float value)](#setIndent-float-) | Visszaadja vagy beállítja az első sor behúzást/függőleges behúzást egy bekezdésben öröklődés nélkül. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. |
| [getTabs()](#getTabs--) | Visszaadja a bekezdés tabulációit. |
| [getFontAlignment()](#getFontAlignment--) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Visszaadja a bekezdés alapértelmezett szakaszformátumát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Visszaadja a bekezdés bullet formátumát. Csak olvasható [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Visszatérési érték:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Visszaadja vagy beállítja a bekezdés mélységét. Az 0 érték undefined értéket jelent. Olvasható/írható short.

**Visszatérési érték:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Visszaadja vagy beállítja a bekezdés mélységét. Az 0 érték undefined értéket jelent. Olvasható/írható short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül. Olvasható/írható [TextAlignment](../../com.aspose.slides/textalignment).

**Visszatérési érték:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül. Olvasható/írható [TextAlignment](../../com.aspose.slides/textalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Visszaadja vagy beállítja a sorok közötti távolságot egy bekezdésben. Pozitív érték százalékot, negatív - pontméretet jelent. Nem alkalmazott öröklődés. Olvasható/írható float.

**Visszatérési érték:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Visszaadja vagy beállítja a sorok közötti távolságot egy bekezdésben. Pozitív érték százalékot, negatív - pontméretet jelent. Nem alkalmazott öröklődés. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Visszaadja vagy beállítja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben határozza meg a fehér teret. Olvasható/írható float.

**Visszatérési érték:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Visszaadja vagy beállítja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben határozza meg a fehér teret. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Visszaadja vagy beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben határozza meg a fehér teret. Olvasható/írható float.

**Visszatérési érték:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Visszaadja vagy beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték pontméretben határozza meg a fehér teret. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Meghatározza, hogy a kelet-ázsiai sortörés használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Meghatározza, hogy a kelet-ázsiai sortörés használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Meghatározza, hogy a jobbról balra írás használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Meghatározza, hogy a jobbról balra írás használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Meghatározza, hogy a latin sortörés használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Meghatározza, hogy a latin sortörés használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Meghatározza, hogy a függőleges központozás használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Meghatározza, hogy a függőleges központozás használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasható/írható float.

**Visszatérési érték:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasható/írható float.

**Visszatérési érték:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Visszaadja vagy beállítja az első sor behúzást/függőleges behúzást egy bekezdésben öröklődés nélkül. A függőleges behúzás negatív értékekkel definiálható. Olvasható/írható float.

**Visszatérési érték:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Visszaadja vagy beállítja az első sor behúzást/függőleges behúzást egy bekezdésben öröklődés nélkül. A függőleges behúzás negatív értékekkel definiálható. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasható/írható float.

**Visszatérési érték:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Visszaadja a bekezdés tabulációit. Nem alkalmazott öröklődés. Csak olvasható [ITabCollection](../../com.aspose.slides/itabcollection).

**Visszatérési érték:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasható/írható [FontAlignment](../../com.aspose.slides/fontalignment).

**Visszatérési érték:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasható/írható [FontAlignment](../../com.aspose.slides/fontalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Visszaadja a bekezdés alapértelmezett szakaszformátumát. Nem alkalmazott öröklődés. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Lekéri a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).