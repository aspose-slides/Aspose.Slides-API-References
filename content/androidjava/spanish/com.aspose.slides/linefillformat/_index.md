---
title: LineFillFormat
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa propiedades para el relleno de líneas.
type: docs
url: /es/com.aspose.slides/linefillformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Representa propiedades para el relleno de líneas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Devuelve o establece el tipo de relleno. |
| [setFillType(byte value)](#setFillType-byte-) | Devuelve o establece el tipo de relleno. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe rotarse con una forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina si el relleno debe rotarse con una forma. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de un relleno sólido. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Devuelve:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determina si el relleno debe rotarse con una forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determina si el relleno debe rotarse con una forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Devuelve el color de un relleno sólido. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Devuelve el formato de relleno degradado. Solo lectura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Devuelve:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Devuelve el formato de relleno de patrón. Solo lectura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Devuelve:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)