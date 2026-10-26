---
title: IFillFormat
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa opciones de formato de relleno.
type: docs
url: /es/com.aspose.slides/ifillformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Representa opciones de formato de relleno.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillType()](#getFillType--) | Devuelve o establece el tipo de relleno. |
| [setFillType(byte value)](#setFillType-byte-) | Devuelve o establece el tipo de relleno. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de relleno. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Devuelve el formato de relleno de imagen. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe rotarse con la forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina si el relleno debe rotarse con la forma. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de relleno efectivos con la herencia aplicada. |
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

Devuelve el color de relleno. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Devuelve el formato de relleno degradado. Solo lectura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Devuelve:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Devuelve el formato de relleno de patrón. Solo lectura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Devuelve:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Devuelve el formato de relleno de imagen. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Determina si el relleno debe rotarse con la forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Determina si el relleno debe rotarse con la forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Obtiene los datos de formato de relleno efectivos con la herencia aplicada.

**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).