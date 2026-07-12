---
title: ErrorBarsFormat
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa las barras de error de una serie de gráfico.
type: docs
url: /es/com.aspose.slides/errorbarsformat/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Representa las barras de error de una serie de gráfico. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Obtiene o establece el tipo de barras de error. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo de barras de error. |
| [getValueType()](#getValueType--) | Representa las posibles formas de determinar la longitud de las barras de error. |
| [setValueType(int value)](#setValueType-int-) | Representa las posibles formas de determinar la longitud de las barras de error. |
| [hasEndCap()](#hasEndCap--) | Especifica que no se dibuja una tapa final en las barras de error. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Especifica que no se dibuja una tapa final en las barras de error. |
| [getValue()](#getValue--) | Obtiene o establece el valor que se utiliza con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. |
| [setValue(float value)](#setValue-float-) | Obtiene o establece el valor que se utiliza con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. |
| [getFormat()](#getFormat--) | Representa el formato de las barras de error. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa el formato de las barras de error. |
| [getChart()](#getChart--) | Devuelve el chart padre. |
| [isVisible()](#isVisible--) | Obtiene o establece la visibilidad de Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece la visibilidad de Error Bars. |
| [getSlide()](#getSlide--) | Devuelve la slide padre de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentation padre de un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Obtiene o establece el tipo de barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Devuelve:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Obtiene o establece el tipo de barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Representa las posibles formas de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor use la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) del punto de datos específico en la colección DataPoints de la serie. En caso de los tipos de valor Fixed, Percentage o StandardDeviation, use la propiedad Value para especificar el valor. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Devuelve:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Representa las posibles formas de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor use la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) del punto de datos específico en la colección DataPoints de la serie. En caso de los tipos de valor Fixed, Percentage o StandardDeviation, use la propiedad Value para especificar el valor. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Especifica que no se dibuja una tapa final en las barras de error. Lectura/escritura boolean.

**Devuelve:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Especifica que no se dibuja una tapa final en las barras de error. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Obtiene o establece el valor que se utiliza con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. En cualquier otro caso devolverá NaN. Lectura/escritura float.

**Devuelve:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Obtiene o establece el valor que se utiliza con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. En cualquier otro caso devolverá NaN. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representa el formato de las barras de error. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representa el formato de las barras de error. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el chart padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Obtiene o establece la visibilidad de Error Bars. Lectura/escritura boolean.

**Devuelve:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Obtiene o establece la visibilidad de Error Bars. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la slide padre de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentation padre de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)