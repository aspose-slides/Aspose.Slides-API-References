---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Representa las propiedades de formato para los elementos de texto del gráfico.
type: docs
url: /es/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Representa las propiedades de formato para los elementos de texto del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Devuelve o establece el texto de anclaje vertical en un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Devuelve o establece el texto de anclaje vertical en un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina la orientación del texto. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina la orientación del texto. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Devuelve o establece el margen derecho (puntos) en un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Devuelve o establece el margen derecho (puntos) en un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Devuelve o establece el margen superior (puntos) en un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Devuelve o establece el margen superior (puntos) en un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Devuelve o establece el margen inferior (puntos) en un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Devuelve o establece el margen inferior (puntos) en un TextFrame. |
| [getWrapText()](#getWrapText--) | Verdadero si el texto se ajusta en los márgenes del TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Verdadero si el texto se ajusta en los márgenes del TextFrame. |
| [getAutofitType()](#getAutofitType--) | Devuelve o establece el modo de autofit del texto. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Devuelve o establece el modo de autofit del texto. |
| [getRotationAngle()](#getRotationAngle--) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Devuelve o establece el texto de anclaje vertical en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Devuelve o establece el texto de anclaje vertical en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Determina la orientación del texto. El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Determina la orientación del texto. El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Devuelve:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Devuelve o establece el margen derecho (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Devuelve:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Devuelve o establece el margen derecho (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Devuelve o establece el margen superior (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Devuelve:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Devuelve o establece el margen superior (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Devuelve o establece el margen inferior (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Devuelve:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Devuelve o establece el margen inferior (puntos) en un TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Verdadero si el texto se ajusta en los márgenes del TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2007/2013). Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Verdadero si el texto se ajusta en los márgenes del TextFrame. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2007/2013). Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Devuelve o establece el modo de autofit del texto. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Devuelve:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Devuelve o establece el modo de autofit del texto. Cambiar esta propiedad puede producir cierta influencia solo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto en la renderización). Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada a él. El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Considere el caso en que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. 
>  Además de esto, el propio cuerpo del texto tiene una rotación de -90 grados 
>  en sentido antihorario aplicada a ella. Entonces la forma resultante parecería estar
>  rotada, pero el texto dentro de ella parecería como si no hubiera sido rotado en absoluto.
```

**Devuelve:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada a él. El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Considere el caso en que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. 
>  Además de esto, el propio cuerpo del texto tiene una rotación de -90 grados 
>  en sentido antihorario aplicada a él. Entonces la forma resultante parecería 
>  estar rotada pero el texto dentro de ella parecería como si no hubiera sido rotado en absoluto.
```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |