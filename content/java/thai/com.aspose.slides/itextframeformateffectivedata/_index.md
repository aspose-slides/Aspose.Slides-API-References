---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติการจัดรูปแบบกรอบข้อความที่มีผล
type: docs
url: /th/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติการจัดรูปแบบกรอบข้อความที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITextFrameFormat](../../com.aspose.slides/itextframeformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมการสืบทอดที่นำไปใช้

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | คืนค่ารูปแบบข้อความที่มีผล |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าขอบซ้าย (จุด) ใน TextFrame |
| [getMarginRight()](#getMarginRight--) | คืนค่าขอบขวา (จุด) ใน TextFrame |
| [getMarginTop()](#getMarginTop--) | คืนค่าขอบบน (จุด) ใน TextFrame |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าขอบล่าง (จุด) ใน TextFrame |
| [getWrapText()](#getWrapText--) | คืนค่าการตัดบรรทัดที่ขอบของ TextFrame |
| [getAnchoringType()](#getAnchoringType--) | คืนค่าการยึดแนวตั้งของข้อความใน TextFrame |
| [getCenterText()](#getCenterText--) | คืนค่าการจัดศูนย์ข้อความในกล่องตามแนวนอน |
| [getTextVerticalType()](#getTextVerticalType--) | คืนค่าการวางแนวข้อความ |
| [getAutofitType()](#getAutofitType--) | คืนค่าโหมดการปรับขนาดข้อความอัตโนมัติ |
| [getColumnCount()](#getColumnCount--) | กำหนดจำนวนคอลัมน์ของข้อความในสี่เหลี่ยมขอบเขต |
| [getColumnSpacing()](#getColumnSpacing--) | กำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยเป็นจุด) |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

คืนค่ารูปแบบข้อความที่มีผล อ่านอย่างเดียว [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**ผลลัพธ์:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

คืนค่าขอบซ้าย (จุด) ใน TextFrame อ่านอย่างเดียว double.

**ผลลัพธ์:**
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

คืนค่าขอบขวา (จุด) ใน TextFrame อ่านอย่างเดียว double.

**ผลลัพธ์:**
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

คืนค่าขอบบน (จุด) ใน TextFrame อ่านอย่างเดียว double.

**ผลลัพธ์:**
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

คืนค่าขอบล่าง (จุด) ใน TextFrame อ่านอย่างเดียว double.

**ผลลัพธ์:**
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

คืนค่าการตัดบรรทัดที่ขอบของ TextFrame อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

คืนค่าการยึดแนวตั้งของข้อความใน TextFrame อ่านอย่างเดียว [TextAnchorType](../../com.aspose.slides/textanchortype).

**ผลลัพธ์:**
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

คืนค่าการจัดศูนย์ข้อความในกล่องตามแนวนอน อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

คืนค่าการวางแนวข้อความ อ่านอย่างเดียว [TextVerticalType](../../com.aspose.slides/textverticaltype).

**ผลลัพธ์:**
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

คืนค่าโหมดการปรับขนาดข้อความอัตโนมัติ อ่านอย่างเดียว [TextAutofitType](../../com.aspose.slides/textautofittype).

**ผลลัพธ์:**
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

กำหนดจำนวนคอลัมน์ของข้อความในสี่เหลี่ยมขอบเขต อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

กำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยเป็นจุด) อ่านอย่างเดียว float.

**ผลลัพธ์:**
float