---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /th/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

แสดงรูปแบบของเซลล์ตาราง.
## เมธอด

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a cell fill properties object. |
| [getBorderLeft()](#getBorderLeft--) | Returns a left border line properties object. |
| [getBorderTop()](#getBorderTop--) | Returns a top border line properties object. |
| [getBorderRight()](#getBorderRight--) | Returns a right border line properties object. |
| [getBorderBottom()](#getBorderBottom--) | Returns a bottom border line properties object. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returns a top-left to bottom-right diagonal line properties object. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returns a bottom-left to top-right diagonal line properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table cell formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติการเติมของเซลล์. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านซ้าย. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากบนซ้ายไปล่างขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


คืนค่าอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากล่างซ้ายไปบนขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


รับหรือกำหนดค่าความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**คืนค่า:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


รับหรือกำหนดค่าความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


รับคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลรวมกับการสืบทอดและสไตล์ตารางที่ใช้.

**คืนค่า:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - เป็น [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).