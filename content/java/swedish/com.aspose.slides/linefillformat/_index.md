---
title: LineFillFormat
second_title: Aspose.Slides för Java API-referens
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
| [getFillType()](#getFillType--) | Returns or sets the fill type. |
| [setFillType(byte value)](#setFillType-byte-) | Returns or sets the fill type. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with a shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determines whether the fill should be rotated with a shape. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the color of a solid fill. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Returns or sets the fill type. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Returns or sets the fill type. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determines whether the fill should be rotated with a shape. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determines whether the fill should be rotated with a shape. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Returns the color of a solid fill. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Returns the gradient fill format. Skrivskyddad [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returnerar:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Returns the pattern fill format. Skrivskyddad [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returnerar:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)