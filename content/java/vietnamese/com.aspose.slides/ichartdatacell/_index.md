---
title: IChartDataCell
second_title: Aspose.Slides cho Java API Reference
description: Biểu diễn ô cho dữ liệu biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Biểu diễn ô cho dữ liệu biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRow()](#getRow--) | Trả về chỉ mục của hàng trong worksheet mà ô nằm trong đó. |
| [getColumn()](#getColumn--) | Trả về chỉ mục của cột trong worksheet mà ô nằm trong đó. |
| [getValue()](#getValue--) | Lấy hoặc đặt giá trị của một ô. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Lấy hoặc đặt giá trị của một ô. |
| [getFormula()](#getFormula--) | Lấy hoặc đặt công thức theo kiểu A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Lấy hoặc đặt công thức theo kiểu A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Lấy hoặc đặt công thức theo kiểu R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Lấy hoặc đặt công thức theo kiểu R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Lấy worksheet. |
| [isHidden()](#isHidden--) | Xác định xem ô có bị ẩn hay không. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Lấy hoặc đặt định dạng hiển thị tùy chỉnh của số và ngày tháng. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Lấy hoặc đặt định dạng hiển thị tùy chỉnh của số và ngày tháng. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Lấy hoặc đặt định dạng hiển thị có sẵn của số và ngày tháng. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Lấy hoặc đặt định dạng hiển thị có sẵn của số và ngày tháng. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Nếu ô chứa công thức, giá trị sẽ được cập nhật dựa trên công thức đó. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Trả về chỉ mục của hàng trong worksheet mà ô nằm trong đó. Chỉ-đọc int.

**Trả về:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Trả về chỉ mục của cột trong worksheet mà ô nằm trong đó. Chỉ-đọc int.

**Trả về:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Lấy hoặc đặt giá trị của một ô. Đọc/ghi Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Lấy hoặc đặt giá trị của một ô. Đọc/ghi Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Lấy hoặc đặt công thức theo kiểu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Trả về:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Lấy hoặc đặt công thức theo kiểu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Lấy hoặc đặt công thức theo kiểu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Trả về:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Lấy hoặc đặt công thức theo kiểu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Lấy worksheet. Chỉ-đọc [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Trả về:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Xác định xem ô có bị ẩn hay không. Chỉ-đọc boolean.

**Trả về:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Lấy hoặc đặt định dạng hiển thị tùy chỉnh của số và ngày tháng. Nếu giá trị trống sẽ sử dụng giá trị PresetNumberFormat. Đọc/ghi String.

**Trả về:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Lấy hoặc đặt định dạng hiển thị tùy chỉnh của số và ngày tháng. Nếu giá trị trống sẽ sử dụng giá trị PresetNumberFormat. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Lấy hoặc đặt định dạng hiển thị có sẵn của số và ngày tháng. Số định dạng phải nằm trong khoảng [0..22] hoặc [37..49]. Đọc/ghi byte.

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

**Trả về:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Lấy hoặc đặt định dạng hiển thị có sẵn của số và ngày tháng. Số định dạng phải nằm trong khoảng [0..22] hoặc [37..49]. Đọc/ghi byte.

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

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


Nếu ô chứa công thức, giá trị sẽ được cập nhật dựa trên công thức đó.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Nếu false, không thực hiện tính toán thực tế. Dùng true để kiểm tra các ngoại lệ có thể xảy ra. |