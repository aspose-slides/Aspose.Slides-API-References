---
title: LineFillFormat
second_title: Aspose.Slides for Java API Referenciája
description: A vonalak kitöltésének tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/linefillformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

A vonalak kitöltésének tulajdonságait képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést a formával kell-e elforgatni. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést a formával kell-e elforgatni. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja egy szilárd kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszaadja:**
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasás/írás [FillType](../../com.aspose.slides/filltype).

**Visszaadja:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasás/írás [FillType](../../com.aspose.slides/filltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Megállapítja, hogy a kitöltést a formával kell-e elforgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszaadja:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Megállapítja, hogy a kitöltést a formával kell-e elforgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Visszaadja egy szilárd kitöltés színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszaadja:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Visszaadja a színátmenetes kitöltés formátumát. Csak olvasható [IGradientFormat](../../com.aspose.slides/igradientformat).

**Visszaadja:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Visszaadja a mintás kitöltés formátumát. Csak olvasható [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszaadja:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)