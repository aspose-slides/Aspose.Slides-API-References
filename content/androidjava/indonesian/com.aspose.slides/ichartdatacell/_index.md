---
title: IChartDataCell
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sel untuk data grafik.
type: docs
url: /id/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Mewakili sel untuk data grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRow()](#getRow--) | Mengembalikan indeks baris lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mengembalikan indeks kolom lembar kerja tempat sel berada. |
| [getValue()](#getValue--) | Mendapatkan atau menetapkan nilai sel. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Mendapatkan atau menetapkan nilai sel. |
| [getFormula()](#getFormula--) | Mendapatkan atau menetapkan formula dalam gaya A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Mendapatkan atau menetapkan formula dalam gaya A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Mendapatkan atau menetapkan formula dalam gaya R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Mendapatkan atau menetapkan formula dalam gaya R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Mendapatkan lembar kerja. |
| [isHidden()](#isHidden--) | Menentukan apakah sel tersembunyi. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Mendapatkan atau menetapkan format tampilan khusus untuk angka dan tanggal. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Mendapatkan atau menetapkan format tampilan khusus untuk angka dan tanggal. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Mendapatkan atau menetapkan format tampilan bawaan untuk angka dan tanggal. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Mendapatkan atau menetapkan format tampilan bawaan untuk angka dan tanggal. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Jika sel berisi formula, nilai akan diperbarui berdasarkan formula tersebut. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

Mengembalikan indeks baris lembar kerja tempat sel berada. Hanya-baca int.

**Mengembalikan:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Mengembalikan indeks kolom lembar kerja tempat sel berada. Hanya-baca int.

**Mengembalikan:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Mendapatkan atau menetapkan nilai sel. Baca/tulis Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Mendapatkan atau menetapkan nilai sel. Baca/tulis Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Mendapatkan atau menetapkan formula dalam gaya A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Mengembalikan:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Mendapatkan atau menetapkan formula dalam gaya A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

Mendapatkan atau menetapkan formula dalam gaya R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Mengembalikan:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

Mendapatkan atau menetapkan formula dalam gaya R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

Mendapatkan lembar kerja. Hanya-baca [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Mengembalikan:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Menentukan apakah sel tersembunyi. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

Mendapatkan atau menetapkan format tampilan khusus untuk angka dan tanggal. Jika nilai kosong, nilai PresetNumberFormat akan digunakan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

Mendapatkan atau menetapkan format tampilan khusus untuk angka dan tanggal. Jika nilai kosong, nilai PresetNumberFormat akan digunakan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

Mendapatkan atau menetapkan format tampilan bawaan untuk angka dan tanggal. Nomor preset harus berada dalam [0..22] atau [37..49]. Baca/tulis byte.

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

**Mengembalikan:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

Mendapatkan atau menetapkan format tampilan bawaan untuk angka dan tanggal. Nomor preset harus berada dalam [0..22] atau [37..49]. Baca/tulis byte.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

Jika sel berisi formula, nilai akan diperbarui berdasarkan formula tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updateValues | boolean | Jika false, tidak ada perhitungan sebenarnya yang akan dilakukan. Gunakan true untuk memeriksa kemungkinan pengecualian. |