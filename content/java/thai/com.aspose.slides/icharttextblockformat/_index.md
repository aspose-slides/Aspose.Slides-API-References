---
title: IChartTextBlockFormat
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ
type: docs
url: /th/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | คืนค่าหรือกำหนดข้อความยึดแนวตั้งใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | คืนค่า或กำหนดข้อความยึดแนวตั้งใน TextFrame. |
| [getCenterText()](#getCenterText--) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [setCenterText(byte value)](#setCenterText-byte-) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดทิศทางของข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดทิศทางของข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่า或กำหนดระยะขอบซ้าย (จุด) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่า或กำหนดระยะขอบซ้าย (จุด) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่า或กำหนดระยะขอบขวา (จุด) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่า或กำหนดระยะขอบขวา (จุด) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่า或กำหนดระยะขอบบน (จุด) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่า或กำหนดระยะขอบบน (จุด) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่า或กำหนดระยะขอบล่าง (จุด) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่า或กำหนดระยะขอบล่าง (จุด) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | true หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | true หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [getAutofitType()](#getAutofitType--) | คืนค่า或กำหนดโหมดการปรับอัตโนมัติของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | คืนค่า或กำหนดโหมดการปรับอัตโนมัติของข้อความ. |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนกำหนดเองที่ใช้กับข้อความภายในกล่องกรอบ. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนกำหนดเองที่ใช้กับข้อความภายในกล่องกรอบ. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

คืนค่า或กำหนดข้อความยึดแนวตั้งใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

คืนค่า或กำหนดข้อความยึดแนวตั้งใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

กำหนดทิศทางของข้อความ. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

กำหนดทิศทางของข้อความ. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

คืนค่า或กำหนดระยะขอบซ้าย (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

คืนค่า或กำหนดระยะขอบซ้าย (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

คืนค่า或กำหนดระยะขอบขวา (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

คืนค่า或กำหนดระยะขอบขวา (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

คืนค่า或กำหนดระยะขอบบน (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

คืนค่า或กำหนดระยะขอบบน (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

คืนค่า或กำหนดระยะขอบล่าง (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

คืนค่า或กำหนดระยะขอบล่าง (จุด) ใน TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

true หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2007/2013). อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

true หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2007/2013). อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

คืนค่า或กำหนดโหมดการปรับอัตโนมัติของข้อความ. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**คืนค่า:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

คืนค่าหรือกำหนดโหมดการปรับอัตโนมัติของข้อความ. การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: DataLabel และ DataLabelFormat (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

ระบุการหมุนกำหนดเองที่ใช้กับข้อความภายในกล่องกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้ว จะถูกประยุกต์แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมนอกเหนือจากข้อความที่มีการหมุนของมันเอง. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปร่างมีการหมุน 90 องศาตามเข็มนาฬิกา 
>  นอกจากนี้ เนื้อความเองก็มีการหมุน -90 องศาทวนเข็มนาฬิกา 
>  แล้วรูปร่างที่ได้จะดูเหมือนถูกหมุน แต่ข้อความภายในดูเหมือนไม่ได้ถูกหมุนเลย
> ```


**คืนค่า:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

ระบุการหมุนกำหนดเองที่ใช้กับข้อความภายในกล่องกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้ว จะถูกประยุกต์แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมนอกเหนือจากข้อความที่มีการหมุนของมันเอง. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปร่างมีการหมุน 90 องศาตามเข็มนาฬิกาที่ถูกนำไปใช้กับมัน. 
>  นอกจากนี้ เนื้อความเองก็มีการหมุน -90 องศา 
>  ทวนเข็มนาฬิกาที่ถูกนำไปใช้กับมัน แล้วรูปร่างที่ได้จะดูเหมือนว่า
>  ถูกหมุน แต่ข้อความภายในดูเหมือนไม่ได้ถูกหมุนเลย.
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |