---
title: ILineFormatEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Android
description: อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งบรรจุคุณสมบัติการจัดรูปแบบเส้นที่มีผล.
type: docs
url: /th/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งบรรจุคุณสมบัติการจัดรูปแบบเส้นที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ILineFormat](../../com.aspose.slides/ilineformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมการใช้การสืบทอด

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | คืนค่ารูปแบบการเติมของเส้น |
| [getSketchFormat()](#getSketchFormat--) | คืนค่ารูปแบบการสเก็ตช์ของเส้น |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของเส้น |
| [getDashStyle()](#getDashStyle--) | คืนค่าสไตล์เส้นขีด |
| [getCustomDashPattern()](#getCustomDashPattern--) | คืนค่ารูปแบบการขีดแบบกำหนดเอง |
| [getCapStyle()](#getCapStyle--) | คืนค่าสไตล์หัวเส้น |
| [getStyle()](#getStyle--) | คืนค่าสไตล์เส้น |
| [getAlignment()](#getAlignment--) | คืนค่าการจัดแนวเส้น |
| [getJoinStyle()](#getJoinStyle--) | คืนค่าสไตล์การเชื่อมต่อของเส้น |
| [getMiterLimit()](#getMiterLimit--) | คืนค่าขีดจำกัดมิตเตอร์ของเส้น |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | คืนค่าสไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | คืนค่าสไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | คืนค่าความกว้างหัวลูกศรที่จุดเริ่มต้นของเส้น |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | คืนค่าความกว้างหัวลูกศรที่จุดสิ้นสุดของเส้น |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | คืนค่าความยาวหัวลูกศรที่จุดเริ่มต้นของเส้น |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | คืนค่าความยาวหัวลูกศรที่จุดสิ้นสุดของเส้น |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | ตรวจสอบว่าอินสแตนซ์ ILineFormatEffectiveData ทั้งสองเท่ากันหรือไม่ |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

คืนค่ารูปแบบการเติมของเส้น อ่านอย่างเดียว [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**ผลลัพธ์:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

คืนค่ารูปแบบการสเก็ตช์ของเส้น อ่านอย่างเดียว [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**ผลลัพธ์:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

คืนค่าความกว้างของเส้น อ่านอย่างเดียว double.

**ผลลัพธ์:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

คืนค่าสไตล์เส้นขีด อ่านอย่างเดียว [LineDashStyle](../../com.aspose.slides/linedashstyle).

**ผลลัพธ์:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

คืนค่ารูปแบบการขีดแบบกำหนดเอง อ่านอย่างเดียว float[].

**ผลลัพธ์:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

คืนค่าสไตล์หัวเส้น อ่านอย่างเดียว [LineCapStyle](../../com.aspose.slides/linecapstyle).

**ผลลัพธ์:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

คืนค่าสไตล์เส้น อ่านอย่างเดียว [LineStyle](../../com.aspose.slides/linestyle).

**ผลลัพธ์:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

คืนค่าการจัดแนวเส้น อ่านอย่างเดียว [LineAlignment](../../com.aspose.slides/linealignment).

**ผลลัพธ์:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

คืนค่าสไตล์การเชื่อมต่อของเส้น อ่านอย่างเดียว [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**ผลลัพธ์:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

คืนค่าขีดจำกัดมิตเตอร์ของเส้น อ่านอย่างเดียว float.

**ผลลัพธ์:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

คืนค่าสไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ผลลัพธ์:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

คืนค่าสไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ผลลัพธ์:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

คืนค่าความกว้างหัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ผลลัพธ์:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

คืนค่าความกว้างหัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ผลลัพธ์:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

คืนความยาวหัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ผลลัพธ์:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

คืนความยาวหัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ผลลัพธ์:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

ตรวจสอบว่าอินสแตนซ์ ILineFormatEffectiveData ทั้งสองเท่ากันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData ที่จะเปรียบเทียบกับ ILineFormatEffectiveData ปัจจุบัน |

**ผลลัพธ์:**
boolean - **true** หาก ILineFormatEffectiveData ที่ระบุเท่ากับ ILineFormatEffectiveData ปัจจุบัน; หากไม่ใช่, **false**.