---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android ผ่าน Java API Reference
description: แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | คืนค่า หรือ ตั้งค่าข้อความยึดแนวตั้งใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | คืนค่า หรือ ตั้งค่าข้อความยึดแนวตั้งใน TextFrame. |
| [getCenterText()](#getCenterText--) | ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [setCenterText(byte value)](#setCenterText-byte-) | ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดทิศทางของข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดทิศทางของข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่า หรือ ตั้งค่าขอบซ้าย (points) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่า หรือ ตั้งค่าขอบซ้าย (points) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่า หรือ ตั้งค่าขอบขวา (points) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่า หรือ ตั้งค่าขอบขวา (points) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่า หรือ ตั้งค่าขอบบน (points) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่า หรือ ตั้งค่าขอบบน (points) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่า หรือ ตั้งค่าขอบล่าง (points) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่า หรือ ตั้งค่าขอบล่าง (points) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | จริง หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | จริง หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [getAutofitType()](#getAutofitType--) | คืนค่า หรือ ตั้งค่าโหมดการปรับอัตโนมัติของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | คืนค่า หรือ ตั้งค่าโหมดการปรับอัตโนมัติของข้อความ. |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

คืนค่า หรือ ตั้งค่าข้อความยึดแนวตั้งใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

คืนค่า หรือ ตั้งค่าข้อความยึดแนวตั้งใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

กำหนดทิศทางของข้อความ. ผลค่าการหมุนของข้อความที่มาจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

กำหนดทิศทางของข้อความ. ผลค่าการหมุนของข้อความที่มาจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

คืนค่า หรือ ตั้งค่าขอบซ้าย (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

คืนค่า หรือ ตั้งค่าขอบซ้าย (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

คืนค่า หรือ ตั้งค่าขอบขวา (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

คืนค่า หรือ ตั้งค่าขอบขวา (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

คืนค่า หรือ ตั้งค่าขอบบน (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

คืนค่า หรือ ตั้งค่าขอบบน (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเทร | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

คืนค่า หรือ ตั้งค่าขอบล่าง (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

คืนค่า หรือ ตั้งค่าขอบล่าง (points) ใน TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

จริง หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2007/2013). อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

จริง หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2007/2013). อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

คืนค่า หรือ ตั้งค่าโหมดการปรับอัตโนมัติของข้อความ. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**คืนค่า:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

คืนค่า หรือ ตั้งค่าโหมดการปรับอัตโนมัติของข้อความ. การเปลี่ยนแปลงของคุณสมบัตินี้อาจส่งผลเฉพาะต่อส่วนของแผนภูมินี้: DataLabel และ DataLabelFormat (รองรับเต็มรูปแบบใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้ว การหมุนจะถูกนำไปใช้แยกจากรูปร่าง. นั่นหมายความว่ารูปร่างอาจมีการหมุนเพิ่มเติมในขณะเดียวกันกับข้อความที่มีการหมุนของตนเอง. ผลค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาแบบตามเข็มนาฬิกา 
>  นอกจากนี้ ข้อความภายในเองมีการหมุน -90 องศาแบบทวนเข็มนาฬิกา 
>  ดังนั้นรูปทรงที่ได้จะดูเหมือนถูกหมุน แต่ข้อความภายในจะดูเหมือนไม่ได้หมุนเลย
> ```


**คืนค่า:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้ว การหมุนจะถูกนำไปใช้แยกจากรูปร่าง. นั่นหมายความว่ารูปร่างอาจมีการหมุนเพิ่มเติมในขณะเดียวกันกับข้อความที่มีการหมุนของตนเอง. ผลค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```markdown
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาแบบตามเข็มนาฬิกา 
>  นอกจากนี้ข้อความภายในเองมีการหมุน -90 องศา 
>  ถูกหมุนทวนเข็มนาฬิกา จากนั้นรูปร่างที่ได้จะดูเหมือนว่า 
>  ถูกหมุน แต่ข้อความภายในดูเหมือนว่าไม่เคยหมุนเลย 
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |