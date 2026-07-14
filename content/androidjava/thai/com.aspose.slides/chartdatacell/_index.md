---
title: ChartDataCell
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเซลล์สำหรับข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartdatacell/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)  
```
public class ChartDataCell implements IChartDataCell
```

แสดงถึงเซลล์สำหรับข้อมูลแผนภูมิ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRow()](#getRow--) | ส่งคืนดัชนีของแถวในชีตงานที่เซลล์ตั้งอยู่. |
| [getColumn()](#getColumn--) | ส่งคืนดัชนีของคอลัมน์ในชีตงานที่เซลล์ตั้งอยู่. |
| [getValue()](#getValue--) | รับหรือกำหนดค่าของเซลล์. |
| [setValue(Object value)](#setValue-java.lang.Object-) | รับหรือกำหนดค่าของเซลล์. |
| [getFormula()](#getFormula--) | รับหรือกำหนดสูตรในรูปแบบ A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | รับหรือกำหนดสูตรในรูปแบบ A1. |
| [getR1C1Formula()](#getR1C1Formula--) | รับหรือกำหนดสูตรในรูปแบบ R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | รับหรือกำหนดสูตรในรูปแบบ R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | รับชีตงาน. |
| [isHidden()](#isHidden--) | กำหนดว่าเซลล์ถูกซ่อนหรือไม่. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | รับหรือกำหนดรูปแบบการแสดงผลแบบกำหนดเองของตัวเลขและวันที่. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | รับหรือกำหนดรูปแบบการแสดงผลแบบกำหนดเองของตัวเลขและวันที่. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | รับหรือกำหนดรูปแบบการแสดงผลในตัวของตัวเลขและวันที่. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | รับหรือกำหนดรูปแบบการแสดงผลในตัวของตัวเลขและวันที่. |
| [calculate(boolean updateValues)](#calculate-boolean-) | หากเซลล์มีสูตร ค่าจะถูกอัปเดตตามสูตรนั้น. |

### getRow() {#getRow--}
```
public final int getRow()
```

ส่งคืนดัชนีของแถวในชีตงานที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

**ส่งคืน:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

ส่งคืนดัชนีของคอลัมน์ในชีตงานที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

**ส่งคืน:**  
int

### getValue() {#getValue--}
```
public final Object getValue()
```

รับหรือกำหนดค่าของเซลล์. อ่าน/เขียน  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**ส่งคืน:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

รับหรือกำหนดค่าของเซลล์. อ่าน/เขียน  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

รับหรือกำหนดสูตรในรูปแบบ A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**ส่งคืน:**  
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

รับหรือกำหนดสูตรในรูปแบบ A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

รับหรือกำหนดสูตรในรูปแบบ R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**ส่งคืน:**  
java.lang.String

### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

รับหรือกำหนดสูตรในรูปแบบ R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

รับชีตงาน. อ่านอย่างเดียว [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**ส่งคืน:**  
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

กำหนดว่าเซลล์ถูกซ่อนหรือไม่. อ่านอย่างเดียว boolean.

**ส่งคืน:**  
boolean

### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

รับหรือกำหนดรูปแบบการแสดงผลแบบกำหนดเองของตัวเลขและวันที่. หากค่าเป็นค่าว่างจะใช้ค่า PresetNumberFormat. อ่าน/เขียน String.

**ส่งคืน:**  
java.lang.String

### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

รับหรือกำหนดรูปแบบการแสดงผลแบบกำหนดเองของตัวเลขและวันที่. หากค่าเป็นค่าว่างจะใช้ค่า PresetNumberFormat. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

รับหรือกำหนดรูปแบบการแสดงผลในตัวของตัวเลขและวันที่. ตัวเลขที่กำหนดต้องอยู่ในช่วง [0..22] หรือ [37..49]. อ่าน/เขียน byte.

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

**ส่งคืน:**  
byte

### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

รับหรือกำหนดรูปแบบการแสดงผลในตัวของตัวเลขและวันที่. ตัวเลขที่กำหนดต้องอยู่ในช่วง [0..22] หรือ [37..49]. อ่าน/เขียน byte.

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

หากเซลล์มีสูตร ค่าจะถูกอัปเดตตามสูตรนั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| updateValues | boolean | หากเป็น false จะไม่มีการคำนวณจริง. ใช้ true เพื่อทำการตรวจสอบข้อยกเว้นที่อาจเกิดขึ้น. |