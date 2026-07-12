---
title: LineFillFormat
second_title: Aspose.Slides für Android über Java API Reference
description: Stellt Eigenschaften für das Füllen von Linien dar.
type: docs
url: /de/com.aspose.slides/linefillformat/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)  
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Stellt Eigenschaften für das Füllen von Linien dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück oder setzt ihn. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Fülltyp zurück oder setzt ihn. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Farbe einer Vollfüllung zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Gradient-Füllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesend long.

**Rückgabe:**  
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Gibt den Fülltyp zurück oder setzt ihn. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Rückgabe:**  
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Gibt den Fülltyp zurück oder setzt ihn. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**  
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Gibt die Farbe einer Vollfüllung zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Gibt das Gradient-Füllformat zurück. Nur lesend [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Gibt das Musterfüllformat zurück. Nur lesend [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Rückgabe:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)