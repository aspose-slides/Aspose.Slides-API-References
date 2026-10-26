---
title: LineFormat
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa el formato de una línea.
type: docs
url: /es/com.aspose.slides/lineformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Representa el formato de una línea.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Devuelve true si el formato de línea no está definido (como recién creado, por defecto). |
| [getFillFormat()](#getFillFormat--) | Devuelve el formato de relleno de una línea. |
| [getSketchFormat()](#getSketchFormat--) | Devuelve el formato de boceto de una línea. |
| [getWidth()](#getWidth--) | Devuelve o establece el ancho de una línea. |
| [setWidth(double value)](#setWidth-double-) | Devuelve o establece el ancho de una línea. |
| [getDashStyle()](#getDashStyle--) | Devuelve o establece el estilo de guión de la línea. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Devuelve o establece el estilo de guión de la línea. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Devuelve o establece el patrón de guiones personalizado. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Devuelve o establece el patrón de guiones personalizado. |
| [getCapStyle()](#getCapStyle--) | Devuelve o establece el estilo de terminación de línea. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Devuelve o establece el estilo de terminación de línea. |
| [getStyle()](#getStyle--) | Devuelve o establece el estilo de línea. |
| [setStyle(byte value)](#setStyle-byte-) | Devuelve o establece el estilo de línea. |
| [getAlignment()](#getAlignment--) | Devuelve o establece la alineación de la línea. |
| [setAlignment(byte value)](#setAlignment-byte-) | Devuelve o establece la alineación de la línea. |
| [getJoinStyle()](#getJoinStyle--) | Devuelve o establece el estilo de unión de las líneas. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Devuelve o establece el estilo de unión de las líneas. |
| [getMiterLimit()](#getMiterLimit--) | Devuelve o establece el límite de inglete de una línea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Devuelve o establece el límite de inglete de una línea. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Devuelve o establece el estilo de punta de flecha al inicio de una línea. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Devuelve o establece el estilo de punta de flecha al inicio de una línea. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Devuelve o establece el estilo de punta de flecha al final de una línea. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Devuelve o establece el estilo de punta de flecha al final de una línea. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Devuelve o establece el ancho de la punta de flecha al inicio de una línea. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Devuelve o establece el ancho de la punta de flecha al inicio de una línea. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Devuelve o establece el ancho de la punta de flecha al final de una línea. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Devuelve o establece el ancho de la punta de flecha al final de una línea. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Devuelve o establece la longitud de la punta de flecha al inicio de una línea. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Devuelve o establece la longitud de la punta de flecha al inicio de una línea. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Devuelve o establece la longitud de la punta de flecha al final de una línea. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Devuelve o establece la longitud de la punta de flecha al final de una línea. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determina si dos instancias de LineFormat son iguales. |
| [getEffective()](#getEffective--) | Obtiene datos de formato de línea efectivos con la herencia aplicada. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara con el objeto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Devuelve:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Devuelve true si el formato de línea no está definido (como recién creado, por defecto). Solo lectura boolean .

**Devuelve:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Devuelve el formato de relleno de una línea. Solo lectura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Devuelve:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Devuelve el formato de boceto de una línea. Solo lectura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Devuelve:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Devuelve o establece el ancho de una línea. Lectura/escritura double .

**Devuelve:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Devuelve o establece el ancho de una línea. Lectura/escritura double .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Devuelve o establece el estilo de guión de la línea. Lectura/escritura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Devuelve:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Devuelve o establece el estilo de guión de la línea. Lectura/escritura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Devuelve o establece el patrón de guiones personalizado. Lectura/escritura float[] .

**Devuelve:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Devuelve o establece el patrón de guiones personalizado. Lectura/escritura float[] .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Devuelve o establece el estilo de terminación de línea. Lectura/escritura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Devuelve:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Devuelve o establece el estilo de terminación de línea. Lectura/escritura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Devuelve o establece el estilo de línea. Lectura/escritura [LineStyle](../../com.aspose.slides/linestyle).

**Devuelve:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Devuelve o establece el estilo de línea. Lectura/escritura [LineStyle](../../com.aspose.slides/linestyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Devuelve o establece la alineación de la línea. Lectura/escritura [LineAlignment](../../com.aspose.slides/linealignment).

**Devuelve:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Devuelve o establece la alineación de la línea. Lectura/escritura [LineAlignment](../../com.aspose.slides/linealignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Devuelve o establece el estilo de unión de las líneas. Lectura/escritura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Devuelve:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Devuelve o establece el estilo de unión de las líneas. Lectura/escritura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Devuelve o establece el límite de inglete de una línea. Lectura/escritura float .

**Devuelve:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Devuelve o establece el límite de inglete de una línea. Lectura/escritura float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Devuelve o establece el estilo de punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Devuelve:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Devuelve o establece el estilo de punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Devuelve o establece el estilo de punta de flecha al final de una línea. Lectura/escritura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Devuelve:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Devuelve o establece el estilo de punta de flecha al final de una línea. Lectura/escritura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Devuelve o establece el ancho de la punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Devuelve:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Devuelve o establece el ancho de la punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Devuelve o establece el ancho de la punta de flecha al final de una línea. Lectura/escritura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Devuelve:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Devuelve o establece el ancho de la punta de flecha al final de una línea. Lectura/escritura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Devuelve o establece la longitud de la punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Devuelve:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Devuelve o establece la longitud de la punta de flecha al inicio de una línea. Lectura/escritura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Devuelve o establece la longitud de la punta de flecha al final de una línea. Lectura/escritura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Devuelve:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Devuelve o establece la longitud de la punta de flecha al final de una línea. Lectura/escritura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Determina si dos instancias de LineFormat son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | El LineFormat a comparar con el LineFormat actual. |

**Devuelve:**
boolean - **true** si el LineFormat especificado es igual al LineFormat actual; de lo contrario, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Obtiene datos de formato de línea efectivos con la herencia aplicada.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).