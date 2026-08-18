---
title: IParagraphFormat
second_title: Aspose.Slides für Java API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften.
type: docs
url: /de/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für einen bestimmten Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefined“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) verwenden, die eine [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-Instanz zurückgibt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBullet()](#getBullet--) | Gibt das Aufzählungsformat des Absatzes zurück. |
| [getDepth()](#getDepth--) | Liefert oder setzt die Tiefe des Absatzes. |
| [setDepth(short value)](#setDepth-short-) | Liefert oder setzt die Tiefe des Absatzes. |
| [getAlignment()](#getAlignment--) | Liefert oder setzt die Textausrichtung in einem Absatz ohne Vererbung. |
| [setAlignment(int value)](#setAlignment-int-) | Liefert oder setzt die Textausrichtung in einem Absatz ohne Vererbung. |
| [getSpaceWithin()](#getSpaceWithin--) | Liefert oder setzt den Abstand zwischen Grundlinien in einem Absatz. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Liefert oder setzt den Abstand zwischen Grundlinien in einem Absatz. |
| [getSpaceBefore()](#getSpaceBefore--) | Liefert oder setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Liefert oder setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. |
| [getSpaceAfter()](#getSpaceAfter--) | Liefert oder setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Liefert oder setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Ermittelt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Ermittelt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [getRightToLeft()](#getRightToLeft--) | Ermittelt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Ermittelt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [getMarginLeft()](#getMarginLeft--) | Liefert oder setzt den linken Rand in einem Absatz ohne Vererbung. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Liefert oder setzt den linken Rand in einem Absatz ohne Vererbung. |
| [getMarginRight()](#getMarginRight--) | Liefert oder setzt den rechten Rand in einem Absatz ohne Vererbung. |
| [setMarginRight(float value)](#setMarginRight-float-) | Liefert oder setzt den rechten Rand in einem Absatz ohne Vererbung. |
| [getIndent()](#getIndent--) | Liefert oder setzt den ersten Zeileneinzug/hängenden Einzug des Absatzes ohne Vererbung. |
| [setIndent(float value)](#setIndent-float-) | Liefert oder setzt den ersten Zeileneinzug/hängenden Einzug des Absatzes ohne Vererbung. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Liefert oder setzt die Standardtabulationsgröße ohne Vererbung. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Liefert oder setzt die Standardtabulationsgröße ohne Vererbung. |
| [getTabs()](#getTabs--) | Gibt die Tabulatoren eines Absatzes zurück. |
| [getFontAlignment()](#getFontAlignment--) | Liefert oder setzt die Schriftartausrichtung in einem Absatz ohne Vererbung. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Liefert oder setzt die Schriftartausrichtung in einem Absatz ohne Vererbung. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Gibt das Standard-Abschnittsformat eines Absatzes zurück. |
| [getEffective()](#getEffective--) | Erhält die wirksamen Absatzformatierungsdaten mit angewandter Vererbung. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Gibt das Aufzählungsformat des Absatzes zurück. Nur lesbar [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Rückgabe:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Liefert oder setzt die Tiefe des Absatzes. Der Wert 0 bedeutet einen undefinierten Wert. Lese-/Schreibzugriff short.

**Rückgabe:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Liefert oder setzt die Tiefe des Absatzes. Der Wert 0 bedeutet einen undefinierten Wert. Lese-/Schreibzugriff short.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Liefert oder setzt die Textausrichtung in einem Absatz ohne Vererbung. Lese-/Schreibzugriff [TextAlignment](../../com.aspose.slides/textalignment).

**Rückgabe:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Liefert oder setzt die Textausrichtung in einem Absatz ohne Vererbung. Lese-/Schreibzugriff [TextAlignment](../../com.aspose.slides/textalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Liefert oder setzt den Abstand zwischen Grundlinien in einem Absatz. Positiver Wert bedeutet Prozent, negativer – Größe in Punkten. Keine Vererbung angewendet. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Liefert oder setzt den Abstand zwischen Grundlinien in einem Absatz. Positiver Wert bedeutet Prozent, negativer – Größe in Punkten. Keine Vererbung angewendet. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Liefert oder setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Liefert oder setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Liefert oder setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Liefert oder setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Ermittelt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Ermittelt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Ermittelt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Ermittelt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese-/Schreibzugriff [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Liefert oder setzt den linken Rand in einem Absatz ohne Vererbung. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Liefert oder setzt den linken Rand in einem Absatz ohne Vererbung. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Liefert oder setzt den rechten Rand in einem Absatz ohne Vererbung. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Liefert oder setzt den rechten Rand in einem Absatz ohne Vererbung. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Liefert oder setzt den ersten Zeileneinzug/hängenden Einzug des Absatzes ohne Vererbung. Hängender Einzug kann mit negativen Werten definiert werden. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Liefert oder setzt den ersten Zeileneinzug/hängenden Einzug des Absatzes ohne Vererbung. Hängender Einzug kann mit negativen Werten definiert werden. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Liefert oder setzt die Standardtabulationsgröße ohne Vererbung. Lese-/Schreibzugriff float.

**Rückgabe:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Liefert oder setzt die Standardtabulationsgröße ohne Vererbung. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur lesbar [ITabCollection](../../com.aspose.slides/itabcollection).

**Rückgabe:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Liefert oder setzt die Schriftartausrichtung in einem Absatz ohne Vererbung. Lese-/Schreibzugriff [FontAlignment](../../com.aspose.slides/fontalignment).

**Rückgabe:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Liefert oder setzt die Schriftartausrichtung in einem Absatz ohne Vererbung. Lese-/Schreibzugriff [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Gibt das Standard-Abschnittsformat eines Absatzes zurück. Keine Vererbung angewendet. Nur lesbar [IPortionFormat](../../com.aspose.slides/iportionformat).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Erhält die wirksamen Absatzformatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).