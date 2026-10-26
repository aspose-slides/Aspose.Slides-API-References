---
title: LineFillFormat
second_title: Aspose.Slides pro Java - reference API
description: Reprezentuje vlastnosti výplně čar.
type: docs
url: /cs/com.aspose.slides/linefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Reprezentuje vlastnosti pro výplň čar.

## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Vrací nebo nastavuje typ výplně. |
| [setFillType(byte value)](#setFillType-byte-) | Vrací nebo nastavuje typ výplně. |
| [getRotateWithShape()](#getRotateWithShape--) | Určuje, zda by měla být výplň otáčena s tvarem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Určuje, zda by měla být výplň otáčena s tvarem. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu plné výplně. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientové výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Vrací nebo nastavuje typ výplně. Čtení/zápis [FillType](../../com.aspose.slides/filltype).

**Vrací:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Vrací nebo nastavuje typ výplně. Čtení/zápis [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Určuje, zda by měla být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Určuje, zda by měla být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Vrací barvu plné výplně. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Vrací formát gradientové výplně. Pouze pro čtení [IGradientFormat](../../com.aspose.slides/igradientformat).

**Vrací:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Vrací formát vzorové výplně. Pouze pro čtení [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Vrací:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)