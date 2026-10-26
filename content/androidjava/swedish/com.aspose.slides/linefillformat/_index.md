---
title: LineFillFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för linjefyllning.
type: docs
url: /sv/com.aspose.slides/linefillformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Representerar egenskaper för linjefyllning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Returnerar eller sätter fyllningstypen. |
| [setFillType(byte value)](#setFillType-byte-) | Returnerar eller sätter fyllningstypen. |
| [getRotateWithShape()](#getRotateWithShape--) | Avgör om fyllningen ska roteras med en form. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Avgör om fyllningen ska roteras med en form. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar färgen på en solid fyllning. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Returnerar eller sätter fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Returnerar eller sätter fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Avgör om fyllningen ska roteras med en form. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Avgör om fyllningen ska roteras med en form. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Returnerar färgen på en solid fyllning. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Returnerar gradientfyllningsformatet. Endast läsning [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returnerar:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Returnerar mönsterfyllningsformatet. Endast läsning [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returnerar:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)