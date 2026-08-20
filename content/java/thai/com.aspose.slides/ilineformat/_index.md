---
title: ILineFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนรูปแบบของเส้น.
type: docs
url: /th/com.aspose.slides/ilineformat/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

เป็นตัวแทนรูปแบบของเส้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | ส่งคืนค่า true หากรูปแบบเส้นยังไม่ได้กำหนด (เช่น เพิ่งสร้าง, ค่าเริ่มต้น). |
| [getFillFormat()](#getFillFormat--) | ส่งคืนรูปแบบการเติมของเส้น. |
| [getSketchFormat()](#getSketchFormat--) | ส่งคืนรูปแบบสเก็ตช์ของเส้น. |
| [getWidth()](#getWidth--) | ส่งคืนหรือกำหนดความกว้างของเส้น. |
| [setWidth(double value)](#setWidth-double-) | ส่งคืนหรือกำหนดความกว้างของเส้น. |
| [getDashStyle()](#getDashStyle--) | ส่งคืนหรือกำหนดรูปแบบการขีดของเส้น. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบการขีดของเส้น. |
| [getCustomDashPattern()](#getCustomDashPattern--) | ส่งคืนหรือกำหนดรูปแบบการขีดแบบกำหนดเอง. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | ส่งคืนหรือกำหนดรูปแบบการขีดแบบกำหนดเอง. |
| [getCapStyle()](#getCapStyle--) | ส่งคืนหรือกำหนดรูปแบบหัวแปลนของเส้น. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบหัวแปลนของเส้น. |
| [getStyle()](#getStyle--) | ส่งคืนหรือกำหนดรูปแบบเส้น. |
| [setStyle(byte value)](#setStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบเส้น. |
| [getAlignment()](#getAlignment--) | ส่งคืนหรือกำหนดการจัดแนวของเส้น. |
| [setAlignment(byte value)](#setAlignment-byte-) | ส่งคืนหรือกำหนดการจัดแนวของเส้น. |
| [getJoinStyle()](#getJoinStyle--) | ส่งคืนหรือกำหนดรูปแบบการเชื่อมต่อของเส้น. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบการเชื่อมต่อของเส้น. |
| [getMiterLimit()](#getMiterLimit--) | ส่งคืนหรือกำหนดขีดจำกัดมิตเตอร์ของเส้น. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | ส่งคืนหรือกำหนดขีดจำกัดมิตเตอร์ของเส้น. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่ปลายของเส้น. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่ปลายของเส้น. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่ปลายของเส้น. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่ปลายของเส้น. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่ปลายของเส้น. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่ปลายของเส้น. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | ตรวจสอบว่าอ็อบเจกต์ LineFormat สองตัวเท่ากันหรือไม่. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบเส้นที่มีผลโดยใช้การสืบทอด. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```


ส่งคืนค่า true หากรูปแบบเส้นยังไม่ได้กำหนด (เช่น เพิ่งสร้าง, ค่าเริ่มต้น). อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```


ส่งคืนรูปแบบการเติมของเส้น. อ่านอย่างเดียว [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**ส่งคืน:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```


ส่งคืนรูปแบบสเก็ตช์ของเส้น. อ่านอย่างเดียว [ISketchFormat](../../com.aspose.slides/isketchformat).

**ส่งคืน:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


ส่งคืนหรือกำหนดความกว้างของเส้น. อ่าน/เขียน double.

**ส่งคืน:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


ส่งคืนหรือกำหนดความกว้างของเส้น. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


ส่งคืนหรือกำหนดรูปแบบการขีดของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**ส่งคืน:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบการขีดของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


ส่งคืนหรือกำหนดรูปแบบการขีดแบบกำหนดเอง. อ่าน/เขียน float[].

**ส่งคืน:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```


ส่งคืนหรือกำหนดรูปแบบการขีดแบบกำหนดเอง. อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


ส่งคืนหรือกำหนดรูปแบบหัวแปลนของเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**ส่งคืน:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบหัวแปลนของเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


ส่งคืนหรือกำหนดรูปแบบเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**ส่งคืน:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


ส่งคืนหรือกำหนดการจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**ส่งคืน:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```


ส่งคืนหรือกำหนดการจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


ส่งคืนหรือกำหนดรูปแบบการเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**ส่งคืน:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบการเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


ส่งคืนหรือกำหนดขีดจำกัดมิตเตอร์ของเส้น. อ่าน/เขียน float.

**ส่งคืน:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```


ส่งคืนหรือกำหนดขีดจำกัดมิตเตอร์ของเส้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ส่งคืน:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ส่งคืน:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```


ส่งคืนหรือกำหนดรูปแบบหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ส่งคืน:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```


ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ส่งคืน:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```


ส่งคืนหรือกำหนดความกว้างของหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ส่งคืน:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```


ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ส่งคืน:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```


ส่งคืนหรือกำหนดความยาวของหัวลูกศรที่ปลายของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```


ตรวจสอบว่าอ็อบเจกต์ LineFormat สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat ที่ต้องการเปรียบเทียบกับ LineFormat ปัจจุบัน. |

**ส่งคืน:**
boolean - **true** หาก LineFormat ที่ระบุเท่ากับ LineFormat ปัจจุบัน; มิฉะนั้น **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```


ดึงข้อมูลการจัดรูปแบบเส้นที่มีผลโดยใช้การสืบทอด.

**ส่งคืน:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).