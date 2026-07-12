---
title: IFillFormatEffectiveData
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Objeto inmutable que contiene propiedades de formato de relleno efectivas.
type: docs
url: /es/com.aspose.slides/ifillformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Objeto inmutable que contiene propiedades de formato de relleno efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [IFillFormat](../../com.aspose.slides/ifillformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillType()](#getFillType--) | Devuelve el tipo de relleno. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de relleno. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Obtiene el color de relleno definido por un esquema de colores. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Devuelve el formato de relleno de imagen. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe girarse con la forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Devuelve el tipo de relleno. Solo lectura [FillType](../../com.aspose.slides/filltype).

**Devuelve:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Devuelve el color de relleno. Solo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Obtiene el color de relleno definido por un esquema de colores. El valor [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indica que el SolidFillColor (\#getSolidFillColor.getSolidFillColor) no es un color de esquema. Solo lectura [SchemeColor](../../com.aspose.slides/schemecolor).

**Devuelve:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Devuelve el formato de relleno degradado. Solo lectura [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Devuelve:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Devuelve el formato de relleno de patrón. Solo lectura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Devuelve:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Devuelve el formato de relleno de imagen. Solo lectura [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Devuelve:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Determina si el relleno debe girarse con la forma. Solo lectura boolean.

**Devuelve:**
boolean