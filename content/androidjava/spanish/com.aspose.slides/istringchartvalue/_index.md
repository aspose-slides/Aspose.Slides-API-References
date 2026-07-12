---
title: IStringChartValue
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/istringchartvalue/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos formas: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
## Métodos

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. |
| [toString()](#toString--) | Devuelve la representación de cadena. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Establece el valor a partir de la celda especificada. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propiedad DataSourceType es DataSourceType.Worksheet, este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Returns:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Devuelve la representación de cadena.

**Returns:**
java.lang.String - Valor de cadena String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Establece el valor a partir de la celda especificada.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Celda. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Si la propiedad DataSourceType es DataSourceType.Worksheet, este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. De lo contrario, devuelve una cadena vacía.

**Returns:**
java.lang.String - Valor de cadena String