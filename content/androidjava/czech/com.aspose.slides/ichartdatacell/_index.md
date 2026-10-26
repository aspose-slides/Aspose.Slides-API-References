---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje buňku pro data grafu.
type: docs
url: /cs/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Představuje buňku pro data grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRow()](#getRow--) | Vrací index řádku listu, ve kterém se buňka nachází. |
| [getColumn()](#getColumn--) | Vrací index sloupce listu, ve kterém se buňka nachází. |
| [getValue()](#getValue--) | Získá nebo nastaví hodnotu buňky. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Získá nebo nastaví hodnotu buňky. |
| [getFormula()](#getFormula--) | Získá nebo nastaví vzorec ve stylu A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Získá nebo nastaví vzorec ve stylu A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Získá nebo nastaví vzorec ve stylu R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Získá nebo nastaví vzorec ve stylu R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Získá list. |
| [isHidden()](#isHidden--) | Určuje, zda je buňka skryta. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Získá nebo nastaví vlastní formát zobrazení čísel a datumů. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Získá nebo nastaví vlastní formát zobrazení čísel a datumů. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Získá nebo nastaví vestavěný formát zobrazení čísel a datumů. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Získá nebo nastaví vestavěný formát zobrazení čísel a datumů. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Pokud buňka obsahuje vzorec, hodnota bude aktualizována na základě tohoto vzorce. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

Vrací index řádku listu, ve kterém se buňka nachází. Pouze pro čtení int.

**Vrací:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Vrací index sloupce listu, ve kterém se buňka nachází. Pouze pro čtení int.

**Vrací:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Získá nebo nastaví hodnotu buňky. Čtení/zápis Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Získá nebo nastaví hodnotu buňky. Čtení/zápis Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Získá nebo nastaví vzorec ve stylu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Vrací:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Získá nebo nastaví vzorec ve stylu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

Získá nebo nastaví vzorec ve stylu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Vrací:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

Získá nebo nastaví vzorec ve stylu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

Získá list. Pouze pro čtení [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Vrací:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Určuje, zda je buňka skryta. Pouze pro čtení boolean.

**Vrací:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

Získá nebo nastaví vlastní formát zobrazení čísel a datumů. Pokud je hodnota prázdná, bude použita hodnota PresetNumberFormat. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

Získá nebo nastaví vlastní formát zobrazení čísel a datumů. Pokud je hodnota prázdná, bude použita hodnota PresetNumberFormat. Čtení/zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

Získá nebo nastaví vestavěný formát zobrazení čísel a datumů. Přednastavené číslo musí být v rozmezí [0..22] nebo [37..49]. Čtení/zápis byte.

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

**Vrací:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

Získá nebo nastaví vestavěný formát zobrazení čísel a datumů. Přednastavené číslo musí být v rozmezí [0..22] nebo [37..49]. Čtení/zápis byte.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

Pokud buňka obsahuje vzorec, hodnota bude aktualizována na základě tohoto vzorce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Pokud je false, neprovedou se žádné skutečné výpočty. Použijte true pro kontrolu možných výjimek. |