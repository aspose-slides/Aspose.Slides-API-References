---
title: IErrorBarsFormat
second_title: Referencia de la API de Aspose.Slides para Android vía Java
description: Representa las barras de error de una serie de gráfico.
type: docs
url: /es/com.aspose.slides/ierrorbarsformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Representa las barras de error de una serie de gráfico. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Métodos

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Obtiene o establece el tipo de barras de error. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo de barras de error. |
| [getValueType()](#getValueType--) | Representa las formas posibles de determinar la longitud de las barras de error. |
| [setValueType(int value)](#setValueType-int-) | Representa las formas posibles de determinar la longitud de las barras de error. |
| [hasEndCap()](#hasEndCap--) | Especifica que no se dibuja una tapa final en las barras de error. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Especifica que no se dibuja una tapa final en las barras de error. |
| [getValue()](#getValue--) | Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. |
| [setValue(float value)](#setValue-float-) | Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. |
| [getFormat()](#getFormat--) | Representa el formato de las barras de error. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa el formato de las barras de error. |
| [isVisible()](#isVisible--) | Obtiene o establece la visibilidad de las barras de error. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece la visibilidad de las barras de error. |

### getType() {#getType--}
```
public abstract int getType()
```

Obtiene o establece el tipo de barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Devuelve:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Obtiene o establece el tipo de barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Representa las formas posibles de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor utilice la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto de datos específico en la colección DataPoints de la serie. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Devuelve:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Representa las formas posibles de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor utilice la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto de datos específico en la colección DataPoints de la serie. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Especifica que no se dibuja una tapa final en las barras de error. Lectura/escritura boolean.

**Devuelve:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Especifica que no se dibuja una tapa final en las barras de error. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. Lectura/escritura float.

**Devuelve:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa el formato de las barras de error. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa el formato de las barras de error. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Obtiene o establece la visibilidad de las barras de error. Lectura/escritura boolean.

**Devuelve:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Obtiene o establece la visibilidad de las barras de error. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |