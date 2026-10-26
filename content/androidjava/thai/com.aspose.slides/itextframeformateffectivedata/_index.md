---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบกรอบข้อความที่มีผล.
type: docs
url: /th/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบกรอบข้อความที่มีผล.

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITextFrameFormat](../../com.aspose.slides/itextframeformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมการประยุกต์ใช้การสืบทอด.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | คืนสไตล์ของข้อความที่มีผล. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าระยะขอบซ้าย (จุด) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่าระยะขอบขวา (จุด) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่าระยะขอบบน (จุด) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าระยะขอบล่าง (จุด) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | คืนค่าว่าข้อความถูกตัดบรรทัดที่ระยะขอบของ TextFrame หรือไม่. |
| [getAnchoringType()](#getAnchoringType--) | คืนค่าข้อความยึดแนวตั้งใน TextFrame. |
| [getCenterText()](#getCenterText--) | คืนค่าว่าข้อความควรอยู่กึ่งกลางในกล่องแนวนอนหรือไม่. |
| [getTextVerticalType()](#getTextVerticalType--) | คืนการจัดแนวของข้อความ. |
| [getAutofitType()](#getAutofitType--) | คืนโหมดการพอดีอัตโนมัติของข้อความ. |
| [getColumnCount()](#getColumnCount--) | กำหนดจำนวนคอลัมน์ของข้อความในสี่เหลี่ยมขอบเขต. |
| [getColumnSpacing()](#getColumnSpacing--) | กำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด). |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

คืนสไตล์ของข้อความที่มีผล. อ่านอย่างเดียว [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**คืนค่า:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

คืนค่าระยะขอบซ้าย (จุด) ใน TextFrame. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

คืนค่าระยะขอบขวา (จุด) ใน TextFrame. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

คืนค่าระยะขอบบน (จุด) ใน TextFrame. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

คืนค่าระยะขอบล่าง (จุด) ใน TextFrame. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

คืนค่าว่าข้อความถูกตัดบรรทัดที่ระยะขอบของ TextFrame หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

คืนค่าข้อความยึดแนวตั้งใน TextFrame. อ่านอย่างเดียว [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**  
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

คืนค่าว่าข้อความควรอยู่กึ่งกลางในกล่องแนวนอนหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

คืนการจัดแนวของข้อความ. อ่านอย่างเดียว [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**  
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

คืนโหมดการพอดีอัตโนมัติของข้อความ. อ่านอย่างเดียว [TextAutofitType](../../com.aspose.slides/textautofittype).

**คืนค่า:**  
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

กำหนดจำนวนคอลัมน์ของข้อความในสี่เหลี่ยมขอบเขต. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

กำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด). อ่านอย่างเดียว float.

**คืนค่า:**  
float