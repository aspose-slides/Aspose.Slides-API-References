---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Grafik verisi için hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Grafik verisi için hücreyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRow()](#getRow--) | Hücrenin bulunduğu çalışma sayfasındaki satırın dizinini döndürür. |
| [getColumn()](#getColumn--) | Hücrenin bulunduğu çalışma sayfasındaki sütunun dizinini döndürür. |
| [getValue()](#getValue--) | Bir hücrenin değerini alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bir hücrenin değerini alır veya ayarlar. |
| [getFormula()](#getFormula--) | A1 stilinde formülü alır veya ayarlar. |
| [setFormula(String value)](#setFormula-java.lang.String-) | A1 stilinde formülü alır veya ayarlar. |
| [getR1C1Formula()](#getR1C1Formula--) | R1C1 stilinde formülü alır veya ayarlar. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | R1C1 stilinde formülü alır veya ayarlar. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Çalışma sayfasını alır. |
| [isHidden()](#isHidden--) | Hücrenin gizli olup olmadığını belirler. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Sayıların ve tarihlerin özel görüntüleme biçimini alır veya ayarlar. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Sayıların ve tarihlerin özel görüntüleme biçimini alır veya ayarlar. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Sayıların ve tarihlerin yerleşik görüntüleme biçimini alır veya ayarlar. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Sayıların ve tarihlerin yerleşik görüntüleme biçimini alır veya ayarlar. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Hücre bir formül içeriyorsa, değer o formüle göre güncellenecektir. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

Hücrenin bulunduğu çalışma sayfasındaki satırın dizinini döndürür. Yalnızca okuma int.

**Döndürür:**  
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Hücrenin bulunduğu çalışma sayfasındaki sütunun dizinini döndürür. Yalnızca okuma int.

**Döndürür:**  
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Bir hücrenin değerini alır veya ayarlar. Okuma/Yazma Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Döndürür:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Bir hücrenin değerini alır veya ayarlar. Okuma/Yazma Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

A1 stilinde formülü alır veya ayarlar.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Döndürür:**  
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

A1 stilinde formülü alır veya ayarlar.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

R1C1 stilinde formülü alır veya ayarlar.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Döndürür:**  
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

R1C1 stilinde formülü alır veya ayarlar.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

Çalışma sayfasını alır. Yalnızca okuma [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Döndürür:**  
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Hücrenin gizli olup olmadığını belirler. Yalnızca okuma boolean.

**Döndürür:**  
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

Sayıların ve tarihlerin özel görüntüleme biçimini alır veya ayarlar. Değer boş ise PresetNumberFormat değeri kullanılacaktır. Okuma/Yazma String.

**Döndürür:**  
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

Sayıların ve tarihlerin özel görüntüleme biçimini alır veya ayarlar. Değer boş ise PresetNumberFormat değeri kullanılacaktır. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

Sayıların ve tarihlerin yerleşik görüntüleme biçimini alır veya ayarlar. Önceden belirlenmiş sayı [0..22] veya [37..49] aralığında olmalıdır. Okuma/Yazma byte.

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

**Döndürür:**  
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

Sayıların ve tarihlerin yerleşik görüntüleme biçimini alır veya ayarlar. Önceden belirlenmiş sayı [0..22] veya [37..49] aralığında olmalıdır. Okuma/Yazma byte.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

Hücre bir formül içeriyorsa, değer o formüle göre güncellenecektir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updateValues | boolean | False ise gerçek bir hesaplama yapılmaz. Olası istisna kontrolü için true kullanın. |