---
title: IStringChartValue
second_title: Referencia de API de Aspose.Slides para Java
description: Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda/celdas del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/istringchartvalue/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda/celdas del libro de trabajo relacionado con el gráfico; 2) como valor literal.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Obtiene o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Obtiene o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [toString()](#toString--) | Devuelve la representación de cadena. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Establece el valor a partir de la celda especificada. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propiedad DataSourceType es DataSourceType.Worksheet, este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Obtiene o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Obtiene o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


Devuelve la representación de cadena.

**Devuelve:**
java.lang.String - Representación de cadena de un valor String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


Establece el valor a partir de la celda especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


Si la propiedad DataSourceType es DataSourceType.Worksheet, este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. De lo contrario, devuelve una cadena vacía.

**Devuelve:**
java.lang.String - Valor de cadena String