---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Diese Klasse enthält die Absatzformatierungseigenschaften.
type: docs
url: /de/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefined“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) verwenden, die eine [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-Instanz zurückgibt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBullet()](#getBullet--) | Gibt das Aufzählungsformat des Absatzes zurück. |
| [getDepth()](#getDepth--) | Gibt die Tiefe des Absatzes zurück oder setzt sie. |
| [setDepth(short value)](#setDepth-short-) | Gibt die Tiefe des Absatzes zurück oder setzt sie. |
| [getAlignment()](#getAlignment--) | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. |
| [setAlignment(int value)](#setAlignment-int-) | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. |
| [getSpaceWithin()](#getSpaceWithin--) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder setzt ihn. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder setzt ihn. |
| [getSpaceBefore()](#getSpaceBefore--) | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [getSpaceAfter()](#getSpaceAfter--) | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [getRightToLeft()](#getRightToLeft--) | Ermittelt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Ermittelt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [setMarginRight(float value)](#setMarginRight-float-) | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. |
| [getIndent()](#getIndent--) | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt ihn. |
| [setIndent(float value)](#setIndent-float-) | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt ihn. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder setzt sie. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder setzt sie. |
| [getTabs()](#getTabs--) | Gibt die Tabulatoren eines Absatzes zurück. |
| [getFontAlignment()](#getFontAlignment--) | Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Gibt das Standardformat eines Absatzabschnitts zurück. |
| [getEffective()](#getEffective--) | Erhält die effektiven Absatzformatierungsdaten mit angewandter Vererbung. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Gibt das Aufzählungsformat des Absatzes zurück. Nur-Lesen [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Rückgabe:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Gibt die Tiefe des Absatzes zurück oder setzt sie. Wert 0 bedeutet undefinierten Wert. Lese/Schreib short.

**Rückgabe:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Gibt die Tiefe des Absatzes zurück oder setzt sie. Wert 0 bedeutet undefinierten Wert. Lese/Schreib short.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese/Schreib [TextAlignment](../../com.aspose.slides/textalignment).

**Rückgabe:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese/Schreib [TextAlignment](../../com.aspose.slides/textalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder setzt ihn. Positiver Wert bedeutet Prozent, negativer – Größe in Punkten. Keine Vererbung angewendet. Lese/Schreib float.

**Rückgabe:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder setzt ihn. Positiver Wert bedeutet Prozent, negativer – Größe in Punkten. Keine Vererbung angewendet. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese/Schreib float.

**Rückgabe:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese/Schreib float.

**Rückgabe:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Ermittelt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Ermittelt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese/Schreib float.

**Rückgabe:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese/Schreib float.

**Rückgabe:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt ihn. Hängender Einzug kann mit negativen Werten definiert werden. Lese/Schreib float.

**Rückgabe:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt ihn. Hängender Einzug kann mit negativen Werten definiert werden. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder setzt sie. Lese/Schreib float.

**Rückgabe:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder setzt sie. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [ITabCollection](../../com.aspose.slides/itabcollection).

**Rückgabe:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese/Schreib [FontAlignment](../../com.aspose.slides/fontalignment).

**Rückgabe:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese/Schreib [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Gibt das Standardformat eines Absatzabschnitts zurück. Keine Vererbung angewendet. Nur-Lesen [IPortionFormat](../../com.aspose.slides/iportionformat).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Erhält die effektiven Absatzformatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).