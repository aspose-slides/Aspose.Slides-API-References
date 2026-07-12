---
title: StringChartValue
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda(s) del libro de trabajo relacionado con el gráfico; 2) como valor literal.
type: docs
url: /es/com.aspose.slides/stringchartvalue/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Representa el valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras: 1) en celda/celdas del libro de trabajo relacionado con el gráfico; 2) como valor literal.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAsCells()](#getAsCells--) | No se permite asignar un valor nulo. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | No se permite asignar un valor nulo. |
| [getAsLiteralString()](#getAsLiteralString--) | Devuelve o establece el valor como cadena literal. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Devuelve o establece el valor como cadena literal. |
| [getData()](#getData--) | Devuelve o establece el objeto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Devuelve o establece el objeto Data. |
| [toString()](#toString--) | Devuelve el valor de cadena. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Establece el valor desde la celda especificada. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propiedad DataSourceType es DataSourceType.Worksheet, entonces este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

No se permite asignar un valor nulo. El valor devuelto siempre no es nulo. Lectura/escritura [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Devuelve:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

No se permite asignar un valor nulo. El valor devuelto siempre no es nulo. Lectura/escritura [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

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

### toString() {#toString--}
```
public String toString()
```

Devuelve datos del valor de cadena. Devuelve nulo si DataSourceType es false y no se asignó ningún valor de cadena.

**Devuelve:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Establece el valor desde la celda especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Si la propiedad DataSourceType es DataSourceType.Worksheet, entonces este método devuelve la dirección de las celdas en el libro de trabajo que representan los datos de cadena. De lo contrario, devuelve una cadena vacía.

**Devuelve:**
java.lang.String