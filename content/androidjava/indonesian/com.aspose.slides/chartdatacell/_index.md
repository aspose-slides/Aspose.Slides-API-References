---
title: ChartDataCell
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sel untuk data bagan.
type: docs
url: /id/com.aspose.slides/chartdatacell/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Mewakili sel untuk data bagan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRow()](#getRow--) | Mengembalikan indeks baris lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mengembalikan indeks kolom lembar kerja tempat sel berada. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai sel. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Mendapatkan atau mengatur nilai sel. |
| [getFormula()](#getFormula--) | Mendapatkan atau mengatur formula dalam gaya A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Mendapatkan atau mengatur formula dalam gaya A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Mendapatkan atau mengatur formula dalam gaya R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Mendapatkan atau mengatur formula dalam gaya R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Mendapatkan lembar kerja. |
| [isHidden()](#isHidden--) | Menentukan apakah sel disembunyikan. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Mendapatkan atau mengatur format tampilan khusus untuk angka dan tanggal. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Mendapatkan atau mengatur format tampilan khusus untuk angka dan tanggal. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Mendapatkan atau mengatur format tampilan bawaan untuk angka dan tanggal. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Mendapatkan atau mengatur format tampilan bawaan untuk angka dan tanggal. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Jika sel berisi formula, nilai akan diperbarui berdasarkan formula tersebut. |
### getRow() {#getRow--}
```
public final int getRow()
```

Mengembalikan indeks baris lembar kerja tempat sel berada. int Baca-saja.

**Mengembalikan:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Mengembalikan indeks kolom lembar kerja tempat sel berada. int Baca-saja.

**Mengembalikan:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Mendapatkan atau mengatur nilai sel. Object Baca/tulis .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Mendapatkan atau mengatur nilai sel. Object Baca/tulis .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
```

Mendapatkan atau mengatur formula dalam gaya A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Mengembalikan:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Mendapatkan atau mengatur formula dalam gaya A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

Mendapatkan atau mengatur formula dalam gaya R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Mengembalikan:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Mendapatkan atau mengatur formula dalam gaya R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Mendapatkan lembar kerja. [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) Baca-saja.

**Mengembalikan:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Menentukan apakah sel disembunyikan. boolean Baca-saja.

**Mengembalikan:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Mendapatkan atau mengatur format tampilan khusus untuk angka dan tanggal. Jika nilai kosong, akan digunakan nilai PresetNumberFormat. String Baca/tulis.

**Mengembalikan:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Mendapatkan atau mengatur format tampilan khusus untuk angka dan tanggal. Jika nilai kosong, akan digunakan nilai PresetNumberFormat. String Baca/tulis.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Mendapatkan atau mengatur format tampilan bawaan untuk angka dan tanggal. Nomor preset harus dalam [0..22] atau [37..49]. byte Baca/tulis.

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


**Mengembalikan:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Mendapatkan atau mengatur format tampilan bawaan untuk angka dan tanggal. Nomor preset harus dalam [0..22] atau [37..49]. byte Baca/tulis.

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

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Jika sel berisi formula, nilai akan diperbarui berdasarkan formula tersebut.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Jika false, tidak ada perhitungan aktual yang akan dilakukan. Gunakan true untuk memeriksa kemungkinan pengecualian. |