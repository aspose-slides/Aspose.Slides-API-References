---
title: StringOrDoubleChartValue
second_title: Aspose.Slides para Android vía Referencia de la API Java
description: Representa un valor de cadena o doble que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/stringordoublechartvalue/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)  
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Representa un valor de cadena o doble que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.

## Métodos

| Método | Descripción |
| --- | --- |
| [getAsCell()](#getAsCell--) | Devuelve o establece la celda de datos del gráfico. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Devuelve o establece la celda de datos del gráfico. |
| [getAsLiteralString()](#getAsLiteralString--) | Devuelve o establece el valor como cadena literal. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Devuelve o establece el valor como cadena literal. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Devuelve o establece el valor como doble literal. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Devuelve o establece el valor como doble literal. |
| [getData()](#getData--) | Devuelve o establece el objeto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Devuelve o establece el objeto Data. |
| [toDouble()](#toDouble--) | Convierte a double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Devuelve o establece la celda de datos del gráfico. Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Devuelve:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Devuelve o establece la celda de datos del gráfico. Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Devuelve o establece el valor como cadena literal. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Devuelve o establece el valor como cadena literal. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Devuelve o establece el valor como doble literal. Lectura/escritura double.

**Devuelve:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Devuelve o establece el valor como doble literal. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Devuelve o establece el objeto Data. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Devuelve o establece el objeto Data. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Convierte a double.

**Devuelve:**
double - Valor doble.