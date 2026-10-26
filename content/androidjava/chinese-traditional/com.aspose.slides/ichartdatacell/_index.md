---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: 表示圖表資料的儲存格。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

表示圖表資料的儲存格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRow()](#getRow--) | 傳回儲存格所在工作表列的索引。 |
| [getColumn()](#getColumn--) | 傳回儲存格所在工作表欄的索引。 |
| [getValue()](#getValue--) | 取得或設定儲存格的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 取得或設定儲存格的值。 |
| [getFormula()](#getFormula--) | 取得或設定 A1 風格的公式。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 取得或設定 A1 風格的公式。 |
| [getR1C1Formula()](#getR1C1Formula--) | 取得或設定 R1C1 風格的公式。 |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | 取得或設定 R1C1 風格的公式。 |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | 取得工作表。 |
| [isHidden()](#isHidden--) | 判斷儲存格是否已隱藏。 |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | 取得或設定數字與日期的自訂顯示格式。 |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | 取得或設定數字與日期的自訂顯示格式。 |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | 取得或設定內建的數字與日期顯示格式。 |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | 取得或設定內建的數字與日期顯示格式。 |
| [calculate(boolean updateValues)](#calculate-boolean-) | 如果儲存格包含公式，值將根據該公式更新。 |
### getRow() {#getRow--}
```
public abstract int getRow()
```

傳回儲存格所在工作表列的索引。唯讀 int.

**傳回值:**  
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

傳回儲存格所在工作表欄的索引。唯讀 int.

**傳回值:**  
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

取得或設定儲存格的值。可讀寫 Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**傳回值:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

取得或設定儲存格的值。可讀寫 Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

取得或設定 A1 風格的公式。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**傳回值:**  
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

取得或設定 A1 風格的公式。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

取得或設定 R1C1 風格的公式。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**傳回值:**  
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

取得或設定 R1C1 風格的公式。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

取得工作表。唯讀 [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)。

**傳回值:**  
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

判斷儲存格是否已隱藏。唯讀 boolean。

**傳回值:**  
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

取得或設定數字與日期的自訂顯示格式。若值為空，將使用 PresetNumberFormat 值。可讀寫 String。

**傳回值:**  
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

取得或設定數字與日期的自訂顯示格式。若值為空，將使用 PresetNumberFormat 值。可讀寫 String。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

取得或設定內建的數字與日期顯示格式。預設編號必須在 [0..22] 或 [37..49] 之間。可讀寫 byte。

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

**傳回值:**  
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

取得或設定內建的數字與日期顯示格式。預設編號必須在 [0..22] 或 [37..49] 之間。可讀寫 byte。

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

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

如果儲存格包含公式，值將根據該公式更新。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| updateValues | boolean | 若為 false，將不執行實際計算。請設為 true 以檢查可能的例外。 |