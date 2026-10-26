---
title: ChartDataCell
second_title: Referencia de la API Java para Aspose.Slides en Android
description: Representa una celda para datos de gráfico.
type: docs
url: /es/com.aspose.slides/chartdatacell/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Representa una celda para datos de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRow()](#getRow--) | Devuelve el índice de la fila de la hoja de cálculo en la que se encuentra la celda. |
| [getColumn()](#getColumn--) | Devuelve el índice de la columna de la hoja de cálculo en la que se encuentra la celda. |
| [getValue()](#getValue--) | Obtiene o establece el valor de una celda. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor de una celda. |
| [getFormula()](#getFormula--) | Obtiene o establece la fórmula en estilo A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Obtiene o establece la fórmula en estilo A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Obtiene o establece la fórmula en estilo R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Obtiene o establece la fórmula en estilo R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Obtiene la hoja de cálculo. |
| [isHidden()](#isHidden--) | Determina si la celda está oculta. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Obtiene o establece el formato de visualización personalizado de números y fechas. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Obtiene o establece el formato de visualización personalizado de números y fechas. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Obtiene o establece el formato de visualización incorporado de números y fechas. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Obtiene o establece el formato de visualización incorporado de números y fechas. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Si la celda contiene una fórmula, el valor se actualizará en base a esa fórmula. |
### getRow() {#getRow--}
```
public final int getRow()
```

Devuelve el índice de la fila de la hoja de cálculo en la que se encuentra la celda. Solo lectura int.

**Devuelve:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Devuelve el índice de la columna de la hoja de cálculo en la que se encuentra la celda. Solo lectura int.

**Devuelve:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Obtiene o establece el valor de una celda. Lectura/escritura Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Obtiene o establece el valor de una celda. Lectura/escritura Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
```

Obtiene o establece la fórmula en estilo A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Devuelve:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Obtiene o establece la fórmula en estilo A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

Obtiene o establece la fórmula en estilo R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Devuelve:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Obtiene o establece la fórmula en estilo R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Obtiene la hoja de cálculo. Solo lectura [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Devuelve:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Determina si la celda está oculta. Solo lectura boolean.

**Devuelve:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Obtiene o establece el formato de visualización personalizado de números y fechas. Si el valor está vacío se usará el valor PresetNumberFormat. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Obtiene o establece el formato de visualización personalizado de números y fechas. Si el valor está vacío se usará el valor PresetNumberFormat. Lectura/escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Obtiene o establece el formato de visualización incorporado de números y fechas. El número preestablecido debe estar en [0..22] o [37..49]. Lectura/escritura byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Devuelve:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Obtiene o establece el formato de visualización incorporado de números y fechas. El número preestablecido debe estar en [0..22] o [37..49]. Lectura/escritura byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Si la celda contiene una fórmula, el valor se actualizará en base a esa fórmula.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Si es false, no se realizará ningún cálculo real. Use true para comprobar posibles excepciones. |