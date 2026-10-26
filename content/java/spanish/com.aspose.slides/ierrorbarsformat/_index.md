---
title: IErrorBarsFormat
second_title: Referencia de API de Aspose.Slides para Java
description: Representa las barras de error de las series del gráfico.
type: docs
url: /es/com.aspose.slides/ierrorbarsformat/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Representa las barras de error de la serie del gráfico. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```

Obtiene o establece el tipo de las barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Obtiene o establece el tipo de las barras de error. Lectura/escritura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Representa formas posibles de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor use la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto de datos específico en la colección DataPoints de la serie. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Devuelve:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Representa formas posibles de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor use la propiedad [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto de datos específico en la colección DataPoints de la serie. Lectura/escritura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

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