---
title: IDoubleChartValue
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa un valor double que puede almacenarse en un documento de presentación pptx de dos formas: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/idoublechartvalue/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Representa un valor double que puede almacenarse en un documento de presentación pptx de dos formas: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Devuelve o establece el valor double literal si DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Devuelve o establece el valor double literal si DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Convierte a double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Devuelve o establece el valor double literal si DataSourceType = Charts.DataSourceType.DoubleLiterals. Lectura/escritura double.

**Devuelve:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Devuelve o establece el valor double literal si DataSourceType = Charts.DataSourceType.DoubleLiterals. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Convierte a double.

**Devuelve:**
double - Valor double.