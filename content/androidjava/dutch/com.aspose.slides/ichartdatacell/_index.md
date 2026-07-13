---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt cel voor diagramgegevens.
type: docs
url: /nl/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Stelt cel voor diagramgegevens.
## Methoden

| Method | Description |
| --- | --- |
| [getRow()](#getRow--) | Retourneert de index van de rij van het werkblad waarin de cel zich bevindt. |
| [getColumn()](#getColumn--) | Retourneert de index van de kolom van het werkblad waarin de cel zich bevindt. |
| [getValue()](#getValue--) | Haalt de waarde van een cel op of stelt deze in. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Haalt de waarde van een cel op of stelt deze in. |
| [getFormula()](#getFormula--) | Haalt de formule in A1-stijl op of stelt deze in. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Haalt de formule in A1-stijl op of stelt deze in. |
| [getR1C1Formula()](#getR1C1Formula--) | Haalt de formule in R1C1-stijl op of stelt deze in. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Haalt de formule in R1C1-stijl op of stelt deze in. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Haalt het werkblad op. |
| [isHidden()](#isHidden--) | Bepaalt of de cel verborgen is. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Haalt het aangepaste weergaveformaat van getallen en datums op of stelt dit in. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Haalt het aangepaste weergaveformaat van getallen en datums op of stelt dit in. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Haalt het ingebouwde weergaveformaat van getallen en datums op of stelt dit in. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Haalt het ingebouwde weergaveformaat van getallen en datums op of stelt dit in. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Als de cel een formule bevat, wordt de waarde bijgewerkt op basis van die formule. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Retourneert de index van de rij van het werkblad waarin de cel zich bevindt. Alleen-lezen int.

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Retourneert de index van de kolom van het werkblad waarin de cel zich bevindt. Alleen-lezen int.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Haalt de waarde van een cel op of stelt deze in. Lezen/schrijven Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Haalt de waarde van een cel op of stelt deze in. Lezen/schrijven Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Haalt de formule in A1-stijl op of stelt deze in.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Haalt de formule in A1-stijl op of stelt deze in.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Haalt de formule in R1C1-stijl op of stelt deze in.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Returns:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Haalt de formule in R1C1-stijl op of stelt deze in.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Haalt het werkblad op. Alleen-lezen [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returns:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Bepaalt of de cel verborgen is. Alleen-lezen boolean.

**Returns:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Haalt het aangepaste weergaveformaat van getallen en datums op of stelt dit in. Als de waarde leeg is, wordt de PresetNumberFormat-waarde gebruikt. Lezen/schrijven String.

**Returns:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Haalt het aangepaste weergaveformaat van getallen en datums op of stelt dit in. Als de waarde leeg is, wordt de PresetNumberFormat-waarde gebruikt. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Haalt het ingebouwde weergaveformaat van getallen en datums op of stelt dit in. Vooraf ingesteld getal moet in [0..22] of [37..49] liggen. Lezen/schrijven byte.

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

**Returns:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Haalt het ingebouwde weergaveformaat van getallen en datums op of stelt dit in. Vooraf ingesteld getal moet in [0..22] of [37..49] liggen. Lezen/schrijven byte.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


Als de cel een formule bevat, wordt de waarde bijgewerkt op basis van die formule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Als false, wordt er geen daadwerkelijke berekening uitgevoerd. Gebruik true om mogelijke uitzonderingen te controleren. |