---
title: ILineFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งบรรจุคุณสมบัติการจัดรูปแบบเส้นที่มีผล
type: docs
url: /th/com.aspose.slides/ilineformateffectivedata/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

อ็อบเจกต์ไม่เปลี่ยนแปลงที่บรรจุคุณสมบัติการจัดรูปแบบเส้นที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ILineFormat](../../com.aspose.slides/ilineformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมการใช้การสืบทอด
## เมธอด

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns the line cap style. |
| [getStyle()](#getStyle--) | Returns the line style. |
| [getAlignment()](#getAlignment--) | Returns the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns the arrowhead length at the end of a line. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determines whether the two ILineFormatEffectiveData instances are equal. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

ส่งคืนรูปแบบการเติมของเส้นหนึ่ง อ่านอย่างเดียว [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**ส่งคืน:**  
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

ส่งคืนรูปแบบสเก็ตช์ของเส้นหนึ่ง อ่านอย่างเดียว [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**ส่งคืน:**  
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

ส่งคืนความกว้างของเส้นหนึ่ง อ่านอย่างเดียว double.

**ส่งคืน:**  
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

ส่งคืนสไตล์การขีดของเส้น อ่านอย่างเดียว [LineDashStyle](../../com.aspose.slides/linedashstyle).

**ส่งคืน:**  
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

ส่งคืนรูปแบบการขีดแบบกำหนดเอง อ่านอย่างเดียว float[].

**ส่งคืน:**  
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

ส่งคืนสไตล์ปลายเส้น อ่านอย่างเดียว [LineCapStyle](../../com.aspose.slides/linecapstyle).

**ส่งคืน:**  
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

ส่งคืนสไตล์เส้น อ่านอย่างเดียว [LineStyle](../../com.aspose.slides/linestyle).

**ส่งคืน:**  
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

ส่งคืนการจัดแนวเส้น อ่านอย่างเดียว [LineAlignment](../../com.aspose.slides/linealignment).

**ส่งคืน:**  
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

ส่งคืนสไตล์การเชื่อมต่อของเส้น อ่านอย่างเดียว [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**ส่งคืน:**  
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

ส่งคืนขีดจำกัดมิดเทอร์ของเส้น อ่านอย่างเดียว float.

**ส่งคืน:**  
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

ส่งคืนสไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ส่งคืน:**  
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

ส่งคืนสไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**ส่งคืน:**  
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

ส่งคืนความกว้างหัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ส่งคืน:**  
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

ส่งคืนความกว้างหัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**ส่งคืน:**  
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

ส่งคืนความยาวหัวลูกศรที่จุดเริ่มต้นของเส้น อ่านอย่างเดียว [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ส่งคืน:**  
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

ส่งคืนความยาวหัวลูกศรที่จุดสิ้นสุดของเส้น อ่านอย่างเดียว [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**ส่งคืน:**  
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

กำหนดว่าทั้งสองอินสแตนซ์ ILineFormatEffectiveData เท่ากันหรือไม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData ที่ต้องการเปรียบเทียบกับ ILineFormatEffectiveData ปัจจุบัน |

**ส่งคืน:**
boolean - **true** ถ้า ILineFormatEffectiveData ที่ระบุเท่ากับ ILineFormatEffectiveData ปัจจุบัน; มิฉะนั้น, **false**.