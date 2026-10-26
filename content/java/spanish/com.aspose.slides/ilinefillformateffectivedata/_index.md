---
title: ILineFillFormatEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que contiene propiedades efectivas de relleno de línea.
type: docs
url: /es/com.aspose.slides/ilinefillformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objeto inmutable que contiene propiedades efectivas de relleno de línea.

--------------------

Esta interfaz se usa como parte de [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillType()](#getFillType--) | Devuelve el tipo de relleno. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de un relleno sólido. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe rotarse con una forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Devuelve el tipo de relleno. Sólo lectura [FillType](../../com.aspose.slides/filltype).

**Devuelve:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Devuelve el color de un relleno sólido. Sólo lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Devuelve el formato de relleno degradado. Sólo lectura [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Devuelve:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Devuelve el formato de relleno de patrón. Sólo lectura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Devuelve:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Determina si el relleno debe rotarse con una forma. Sólo lectura boolean.

**Devuelve:**
boolean