---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta una cella per i dati del grafico.
type: docs
url: /it/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Rappresenta una cella per i dati del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRow()](#getRow--) | Restituisce l'indice della riga del foglio di lavoro in cui si trova la cella. |
| [getColumn()](#getColumn--) | Restituisce l'indice della colonna del foglio di lavoro in cui si trova la cella. |
| [getValue()](#getValue--) | Ottiene o imposta il valore di una cella. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore di una cella. |
| [getFormula()](#getFormula--) | Ottiene o imposta la formula in stile A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Ottiene o imposta la formula in stile A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Ottiene o imposta la formula in stile R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Ottiene o imposta la formula in stile R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Ottiene il foglio di lavoro. |
| [isHidden()](#isHidden--) | Determina se la cella è nascosta. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Se la cella contiene una formula, il valore verrà aggiornato in base a quella formula. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

Restituisce l'indice della riga del foglio di lavoro in cui si trova la cella. Solo lettura int.

**Restituisce:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Restituisce l'indice della colonna del foglio di lavoro in cui si trova la cella. Solo lettura int.

**Restituisce:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Ottiene o imposta il valore di una cella. Lettura/scrittura Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Restituisce:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Ottiene o imposta il valore di una cella. Lettura/scrittura Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Ottiene o imposta la formula in stile A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Restituisce:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Ottiene o imposta la formula in stile A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

Ottiene o imposta la formula in stile R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Restituisce:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

Ottiene o imposta la formula in stile R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

Ottiene il foglio di lavoro. Solo lettura [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Restituisce:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Determina se la cella è nascosta. Solo lettura boolean.

**Restituisce:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. Se il valore è vuoto verrà utilizzato il valore PresetNumberFormat. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. Se il valore è vuoto verrà utilizzato il valore PresetNumberFormat. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49]. Lettura/scrittura byte.

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


**Restituisce:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49]. Lettura/scrittura byte.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

Se la cella contiene una formula, il valore verrà aggiornato in base a quella formula.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| updateValues | boolean | Se false, non verrà eseguita alcuna reale calcolazione. Usa true per verificare possibili eccezioni. |