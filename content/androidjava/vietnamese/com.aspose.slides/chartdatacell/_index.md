---
title: ChartDataCell
second_title: Aspose.Slides for Android qua Tham chiếu API Java
description: Biểu diễn ô cho dữ liệu biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartdatacell/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Biểu diễn ô cho dữ liệu biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRow()](#getRow--) | Trả về chỉ số của hàng trong bảng tính mà ô nằm trong đó. |
| [getColumn()](#getColumn--) | Trả về chỉ số của cột trong bảng tính mà ô nằm trong đó. |
| [getValue()](#getValue--) | Lấy hoặc đặt giá trị của một ô. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Lấy hoặc đặt giá trị của một ô. |
| [getFormula()](#getFormula--) | Lấy hoặc đặt công thức theo kiểu A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Lấy hoặc đặt công thức theo kiểu A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Lấy hoặc đặt công thức theo kiểu R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Lấy hoặc đặt công thức theo kiểu R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Lấy bảng tính. |
| [isHidden()](#isHidden--) | Xác định xem ô có bị ẩn hay không. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Lấy hoặc đặt định dạng hiển thị tùy chỉnh cho số và ngày. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Lấy hoặc đặt định dạng hiển thị tùy chỉnh cho số và ngày. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Lấy hoặc đặt định dạng hiển thị tích hợp cho số và ngày. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Lấy hoặc đặt định dạng hiển thị tích hợp cho số và ngày. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Nếu ô chứa công thức, giá trị sẽ được cập nhật dựa trên công thức đó. |
### getRow() {#getRow--}
```
public final int getRow()
```

Trả về chỉ số của hàng trong bảng tính mà ô nằm trong đó. Chỉ đọc int.

**Trả về:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Trả về chỉ số của cột trong bảng tính mà ô nằm trong đó. Chỉ đọc int.

**Trả về:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Lấy hoặc đặt giá trị của một ô. Đọc/ghi Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Lấy hoặc đặt giá trị của một ô. Đọc/ghi Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
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
public final void setFormula(String value)
```

Lấy hoặc đặt công thức theo kiểu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
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
public final void setR1C1Formula(String value)
```

Lấy hoặc đặt công thức theo kiểu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Lấy bảng tính. Chỉ đọc [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Trả về:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Xác định xem ô có bị ẩn hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Lấy hoặc đặt định dạng hiển thị tùy chỉnh cho số và ngày. Nếu giá trị rỗng sẽ sử dụng giá trị PresetNumberFormat. Đọc/ghi String.

**Trả về:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Lấy hoặc đặt định dạng hiển thị tùy chỉnh cho số và ngày. Nếu giá trị rỗng sẽ sử dụng giá trị PresetNumberFormat. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Lấy hoặc đặt định dạng hiển thị tích hợp cho số và ngày. Số định dạng phải nằm trong khoảng [0..22] hoặc [37..49]. Đọc/ghi byte.

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

**Trả về:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Lấy hoặc đặt định dạng hiển thị tích hợp cho số và ngày. Số định dạng phải nằm trong khoảng [0..22] hoặc [37..49]. Đọc/ghi byte.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Nếu ô chứa công thức, giá trị sẽ được cập nhật dựa trên công thức đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| updateValues | boolean | Nếu false, không có phép tính thực tế nào sẽ được thực hiện. Dùng true để kiểm tra các ngoại lệ có thể xảy ra. |