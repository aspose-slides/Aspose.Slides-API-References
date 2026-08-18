---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /de/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Stellt die Stilreferenz einer Form dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLineColor()](#getLineColor--) | Gibt die Konturfarbe einer Form zurück. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Gibt den Spaltenindex der Linie in einer Stilmatrix zurück oder setzt ihn. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Gibt den Spaltenindex der Linie in einer Stilmatrix zurück oder setzt ihn. |
| [getFillColor()](#getFillColor--) | Gibt die Füllfarbe einer Form zurück. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Gibt den Füllspaltenindex einer Form in Stilmatrizen zurück oder setzt ihn. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Gibt den Füllspaltenindex einer Form in Stilmatrizen zurück oder setzt ihn. |
| [getEffectColor()](#getEffectColor--) | Gibt die Effektfarbe einer Form zurück. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Gibt den Effektspaltenindex einer Form in einer Stilmatrix zurück oder setzt ihn. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Gibt den Effektspaltenindex einer Form in einer Stilmatrix zurück oder setzt ihn. |
| [getFontColor()](#getFontColor--) | Gibt die Schriftfarbe einer Form zurück. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Gibt den Schriftindex einer Form in einer Schriftartsammlung zurück oder setzt ihn. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Gibt den Schriftindex einer Form in einer Schriftartsammlung zurück oder setzt ihn. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Gibt die Konturfarbe einer Form zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Gibt den Spaltenindex der Linie in einer Stilmatrix zurück oder setzt ihn. Lese/Schreib int.

**Rückgabe:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Gibt den Spaltenindex der Linie in einer Stilmatrix zurück oder setzt ihn. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Gibt die Füllfarbe einer Form zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Gibt den Füllspaltenindex einer Form in Stilmatrizen zurück oder setzt ihn. 0 bedeutet keine Füllung, ein positiver Wert – Index in den Füllstilen des Themas, ein negativer Wert – Index in den Hintergrundstilen des Themas. Lese/Schreib short.

**Rückgabe:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Gibt den Füllspaltenindex einer Form in Stilmatrizen zurück oder setzt ihn. 0 bedeutet keine Füllung, ein positiver Wert – Index in den Füllstilen des Themas, ein negativer Wert – Index in den Hintergrundstilen des Themas. Lese/Schreib short.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Gibt die Effektfarbe einer Form zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Gibt den Effektspaltenindex einer Form in einer Stilmatrix zurück oder setzt ihn. Lese/Schreib long.

**Rückgabe:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Gibt den Effektspaltenindex einer Form in einer Stilmatrix zurück oder setzt ihn. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Gibt die Schriftfarbe einer Form zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Gibt den Schriftindex einer Form in einer Schriftartsammlung zurück oder setzt ihn. Lese/Schreib [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Rückgabe:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Gibt den Schriftindex einer Form in einer Schriftartsammlung zurück oder setzt ihn. Lese/Schreib [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |