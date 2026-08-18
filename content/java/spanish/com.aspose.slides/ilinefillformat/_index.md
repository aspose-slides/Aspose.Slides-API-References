---
title: ILineFillFormat
second_title: Referencia de API de Aspose.Slides para Java
description: Representa propiedades para el relleno de líneas.
type: docs
url: /es/com.aspose.slides/ilinefillformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Representa propiedades para el relleno de líneas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillType()](#getFillType--) | Devuelve o establece el tipo de relleno. |
| [setFillType(byte value)](#setFillType-byte-) | Devuelve o establece el tipo de relleno. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de un relleno sólido. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe rotarse con una forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina si el relleno debe rotarse con una forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Devuelve:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Devuelve el color de un relleno sólido. Sólo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Devuelve el formato de relleno degradado. Sólo lectura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Devuelve:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Devuelve el formato de relleno de patrón. Sólo lectura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Devuelve:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Determina si el relleno debe rotarse con una forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Determina si el relleno debe rotarse con una forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |