---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /de/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Unveränderliches Objekt, das wirksame Absatzformatierungseigenschaften enthält.

Dieses Interface wird zusammen mit dem [IParagraphFormat](../../com.aspose.slides/iparagraphformat) Interface verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Gibt ein Aufzählungsformat eines Absatzes zurück. |
| [getDepth()](#getDepth--) | Gibt die Tiefe eines Absatzes zurück. |
| [getAlignment()](#getAlignment--) | Gibt die Textausrichtung in einem Absatz zurück. |
| [getSpaceWithin()](#getSpaceWithin--) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück. |
| [getSpaceBefore()](#getSpaceBefore--) | Gibt den Abstand vor der ersten Zeile in einem Absatz zurück. |
| [getSpaceAfter()](#getSpaceAfter--) | Gibt den Abstand nach der letzten Zeile in einem Absatz zurück. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [getRightToLeft()](#getRightToLeft--) | Bestimmt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand in einem Absatz zurück. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand in einem Absatz zurück. |
| [getIndent()](#getIndent--) | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes zurück. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Gibt die Standard-Tabulationsgröße zurück. |
| [getTabs()](#getTabs--) | Gibt die Tabulatoren eines Absatzes zurück. |
| [getFontAlignment()](#getFontAlignment--) | Gibt die Schriftausrichtung in einem Absatz zurück. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Gibt das Standard-Abschnittsformat eines Absatzes zurück. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Gibt ein Aufzählungsformat eines Absatzes zurück. Nur lesbar [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Rückgabe:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Gibt die Tiefe eines Absatzes zurück. Nur lesbar short.

**Rückgabe:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Gibt die Textausrichtung in einem Absatz zurück. Nur lesbar [TextAlignment](../../com.aspose.slides/textalignment).

**Rückgabe:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Gibt den Abstand zwischen Grundlinien in einem Absatz zurück. Nur lesbar float.

**Rückgabe:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Gibt den Abstand vor der ersten Zeile in einem Absatz zurück. Nur lesbar float.

**Rückgabe:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Gibt den Abstand nach der letzten Zeile in einem Absatz zurück. Nur lesbar float.

**Rückgabe:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Nur lesbar boolean.

**Rückgabe:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Bestimmt, ob die Rechts-nach-Links-Schreibung in einem Absatz verwendet wird. Nur lesbar boolean.

**Rückgabe:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Nur lesbar boolean.

**Rückgabe:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Nur lesbar boolean.

**Rückgabe:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Gibt den linken Rand in einem Absatz zurück. Nur lesbar float.

**Rückgabe:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Gibt den rechten Rand in einem Absatz zurück. Nur lesbar float.

**Rückgabe:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes zurück. Hängender Einzug kann mit negativen Werten definiert werden. Nur lesbar float.

**Rückgabe:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Gibt die Standard-Tabulationsgröße zurück. Nur lesbar float.

**Rückgabe:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Gibt die Tabulatoren eines Absatzes zurück. Nur lesbar ITabEffectiveData[].

**Rückgabe:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Gibt die Schriftausrichtung in einem Absatz zurück. Nur lesbar [FontAlignment](../../com.aspose.slides/fontalignment).

**Rückgabe:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Gibt das Standard-Abschnittsformat eines Absatzes zurück. Nur lesbar [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Rückgabe:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)