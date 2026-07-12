---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android a través de la referencia de API Java
description: Representa un valor de cadena o doble que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en la(s) celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/istringordoublechartvalue/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Representa un valor de cadena o dobles que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en la(s) celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Devuelve o establece el doble literal si la propiedad DataSourceType es DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Devuelve o establece el doble literal si la propiedad DataSourceType es DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Convierte el valor a double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Devuelve o establece el doble literal si la propiedad DataSourceType es DataSourceType.DoubleLiterals. Lectura/escritura double.

**Devuelve:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Devuelve o establece el doble literal si la propiedad DataSourceType es DataSourceType.DoubleLiterals. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Convierte el valor a double.

**Devuelve:**
double - Valor double