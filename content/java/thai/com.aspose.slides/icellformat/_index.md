---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: แสดงรูปแบบของเซลล์ตาราง.
type: docs
url: /th/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

แสดงรูปแบบของเซลล์ตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมของเซลล์. |
| [getBorderLeft()](#getBorderLeft--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านซ้าย. |
| [getBorderTop()](#getBorderTop--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านบน. |
| [getBorderRight()](#getBorderRight--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านขวา. |
| [getBorderBottom()](#getBorderBottom--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านล่าง. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากซ้ายบนไปขวาล่าง. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากซ้ายล่างไปขวาบน. |
| [getTransparency()](#getTransparency--) | รับหรือกำหนดค่าความโปร่งแสงของสีเติม. |
| [setTransparency(float value)](#setTransparency-float-) | รับหรือกำหนดค่าความโปร่งแสงของสีเติม. |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบของเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ตารางที่นำไปใช้. |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมของเซลล์. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านซ้าย. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นขอบด้านล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากซ้ายบนไปขวาล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติเส้นทแยงมุมจากซ้ายล่างไปขวาบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

รับหรือกำหนดค่าความโปร่งแสงของสีเติม. อ่าน/เขียน  float .

**คืนค่า:**
float

### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

รับหรือกำหนดค่าความโปร่งแสงของสีเติม. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

รับคุณสมบัติการจัดรูปแบบของเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ตารางที่นำไปใช้.

**คืนค่า:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - หนึ่ง [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).