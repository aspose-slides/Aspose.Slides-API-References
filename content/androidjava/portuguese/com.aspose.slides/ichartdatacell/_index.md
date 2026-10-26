---
title: IChartDataCell
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma célula para dados de gráfico.
type: docs
url: /pt/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Representa uma célula para dados de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRow()](#getRow--) | Retorna o índice da linha da planilha na qual a célula está localizada. |
| [getColumn()](#getColumn--) | Retorna o índice da coluna da planilha na qual a célula está localizada. |
| [getValue()](#getValue--) | Obtém ou define o valor de uma célula. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtém ou define o valor de uma célula. |
| [getFormula()](#getFormula--) | Obtém ou define a fórmula no estilo A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Obtém ou define a fórmula no estilo A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Obtém ou define a fórmula no estilo R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Obtém ou define a fórmula no estilo R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Obtém a planilha. |
| [isHidden()](#isHidden--) | Determina se a célula está oculta. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Obtém ou define o formato de exibição personalizado de números e datas. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Obtém ou define o formato de exibição personalizado de números e datas. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Obtém ou define o formato de exibição interno de números e datas. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Obtém ou define o formato de exibição interno de números e datas. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Se a célula contiver uma fórmula, o valor será atualizado com base nessa fórmula. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Retorna o índice da linha da planilha na qual a célula está localizada. **Somente leitura** int.

**Retorna:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Retorna o índice da coluna da planilha na qual a célula está localizada. **Somente leitura** int.

**Retorna:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtém ou define o valor de uma célula. **Leitura/gravação** Object.

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


Obtém ou define o valor de uma célula. **Leitura/gravação** Object.

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


Obtém a planilha. **Somente leitura** [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Retorna:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Determina se a célula está oculta. **Somente leitura** boolean.

**Retorna:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Obtém ou define o formato de exibição personalizado de números e datas. Se o valor estiver vazio, será usado o valor PresetNumberFormat. **Leitura/gravação** String.

**Retorna:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Obtém ou define o formato de exibição personalizado de números e datas. Se o valor estiver vazio, será usado o valor PresetNumberFormat. **Leitura/gravação** String.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Obtém ou define o formato de exibição interno de números e datas. O número predefinido deve estar em [0..22] ou [37..49]. **Leitura/gravação** byte.

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


Obtém ou define o formato de exibição interno de números e datas. O número predefinido deve estar em [0..22] ou [37..49]. **Leitura/gravação** byte.

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


Se a célula contiver uma fórmula, o valor será atualizado com base nessa fórmula.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Se false, nenhum cálculo real será realizado. Use true para possível verificação de exceções. |