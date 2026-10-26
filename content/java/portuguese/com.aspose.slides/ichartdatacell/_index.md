---
title: IChartDataCell
second_title: Aspose.Slides for Java API Reference
description: Represents cell for chart data.
type: docs
url: /pt/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Representa uma célula para dados de gráfico.
## Métodos

| Method | Description |
| --- | --- |
| [getRow()](#getRow--) | Returns the index of the row of worksheet in which the cell is located. |
| [getColumn()](#getColumn--) | Returns the index of the column of worksheet in which the cell is located. |
| [getValue()](#getValue--) | Gets or sets the value of a cell. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value of a cell. |
| [getFormula()](#getFormula--) | Gets or sets the formula in A1-style. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Gets or sets the formula in A1-style. |
| [getR1C1Formula()](#getR1C1Formula--) | Gets or sets the formula in R1C1-style. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Gets or sets the formula in R1C1-style. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Gets the worksheet. |
| [isHidden()](#isHidden--) | Determines whether the cell is hidden. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Gets or sets the custom display format of numbers and dates. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Gets or sets the custom display format of numbers and dates. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Gets or sets the built-in display format of numbers and dates. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Gets or sets the built-in display format of numbers and dates. |
| [calculate(boolean updateValues)](#calculate-boolean-) | If the cell contains a formula, the value will be updated base on that formula. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Retorna o índice da linha da planilha na qual a célula está localizada. Somente leitura int.

**Retorna:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Retorna o índice da coluna da planilha na qual a célula está localizada. Somente leitura int.

**Retorna:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtém ou define o valor de uma célula. Leitura/Gravação Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Obtém ou define o valor de uma célula. Leitura/Gravação Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Obtém ou define a fórmula no estilo A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Retorna:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Obtém ou define a fórmula no estilo A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Obtém ou define a fórmula no estilo R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Retorna:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Obtém ou define a fórmula no estilo R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Obtém a planilha. Somente leitura [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Retorna:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Determina se a célula está oculta. Somente leitura boolean.

**Retorna:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Obtém ou define o formato de exibição personalizado de números e datas. Se o valor estiver vazio, será usado PresetNumberFormat value. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Obtém ou define o formato de exibição personalizado de números e datas. Se o valor estiver vazio, será usado PresetNumberFormat value. Leitura/Gravação String.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Obtém ou define o formato de exibição interno de números e datas. O número predefinido deve estar em [0..22] ou [37..49]. Leitura/Gravação byte.

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
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Retorna:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Obtém ou define o formato de exibição interno de números e datas. O número predefinido deve estar em [0..22] ou [37..49]. Leitura/Gravação byte.

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
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


Se a célula contém uma fórmula, o valor será atualizado com base nessa fórmula.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Se false, nenhum cálculo real será executado. Use true para verificar possíveis exceções. |