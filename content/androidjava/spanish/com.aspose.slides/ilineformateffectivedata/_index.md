---
title: ILineFormatEffectiveData
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Objeto inmutable que contiene propiedades de formato de línea efectivas.
type: docs
url: /es/com.aspose.slides/ilineformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Objeto inmutable que contiene propiedades de formato de línea efectivas.

--------------------

Esta interfaz se utiliza junto con la interfaz [ILineFormat](../../com.aspose.slides/ilineformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns the line cap style. |
| [getStyle()](#getStyle--) | Returns the line style. |
| [getAlignment()](#getAlignment--) | Returns the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns the arrowhead length at the end of a line. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determines whether the two ILineFormatEffectiveData instances are equal. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Devuelve el formato de relleno de una línea. Solo lectura [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Devuelve:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Devuelve el formato de boceto de una línea. Solo lectura [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Devuelve:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Devuelve el ancho de una línea. Solo lectura double.

**Devuelve:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Devuelve el estilo de guión de la línea. Solo lectura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Devuelve:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Devuelve el patrón de guiones personalizado. Solo lectura float[].

**Devuelve:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Devuelve el estilo de extremo de línea. Solo lectura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Devuelve:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Devuelve el estilo de línea. Solo lectura [LineStyle](../../com.aspose.slides/linestyle).

**Devuelve:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Devuelve la alineación de la línea. Solo lectura [LineAlignment](../../com.aspose.slides/linealignment).

**Devuelve:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Devuelve el estilo de unión de líneas. Solo lectura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Devuelve:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Devuelve el límite de inglete de una línea. Solo lectura float.

**Devuelve:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Devuelve el estilo de la punta de flecha al inicio de una línea. Solo lectura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Devuelve:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Devuelve el estilo de la punta de flecha al final de una línea. Solo lectura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Devuelve:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Devuelve el ancho de la punta de flecha al inicio de una línea. Solo lectura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Devuelve:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Devuelve el ancho de la punta de flecha al final de una línea. Solo lectura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Devuelve:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Devuelve la longitud de la punta de flecha al inicio de una línea. Solo lectura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Devuelve:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Devuelve la longitud de la punta de flecha al final de una línea. Solo lectura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Devuelve:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Determina si las dos instancias de ILineFormatEffectiveData son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | El ILineFormatEffectiveData a comparar con el ILineFormatEffectiveData actual. |

**Devuelve:**
boolean - **true** si el ILineFormatEffectiveData especificado es igual al ILineFormatEffectiveData actual; de lo contrario, **false**.