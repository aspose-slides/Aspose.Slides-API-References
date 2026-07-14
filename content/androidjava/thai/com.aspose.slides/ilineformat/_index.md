---
title: ILineFormat
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงรูปแบบของเส้น.
type: docs
url: /th/com.aspose.slides/ilineformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

เป็นตัวแทนของรูปแบบของเส้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | คืนค่า true หากรูปแบบของเส้นไม่ได้กำหนด (เป็นค่าเริ่มต้นเมื่อเพิ่งสร้าง). |
| [getFillFormat()](#getFillFormat--) | คืนค่ารูปแบบการเติมของเส้น. |
| [getSketchFormat()](#getSketchFormat--) | คืนค่ารูปแบบสเก็ตช์ของเส้น. |
| [getWidth()](#getWidth--) | คืนค่าหรือกำหนดความกว้างของเส้น. |
| [setWidth(double value)](#setWidth-double-) | คืนค่าหรือกำหนดความกว้างของเส้น. |
| [getDashStyle()](#getDashStyle--) | คืนค่าหรือกำหนดสไตล์การขีดของเส้น. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | คืนค่าหรือกำหนดสไตล์การขีดของเส้น. |
| [getCustomDashPattern()](#getCustomDashPattern--) | คืนค่า หรือกำหนดรูปแบบการขีดแบบกำหนดเอง. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | คืนค่า หรือกำหนดรูปแบบการขีดแบบกำหนดเอง. |
| [getCapStyle()](#getCapStyle--) | คืนค่าหรือกำหนดสไตล์การปลายเส้น. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | คืนค่าหรือกำหนดสไตล์การปลายเส้น. |
| [getStyle()](#getStyle--) | คืนค่าหรือกำหนดสไตล์ของเส้น. |
| [setStyle(byte value)](#setStyle-byte-) | คืนค่าหรือกำหนดสไตล์ของเส้น. |
| [getAlignment()](#getAlignment--) | คืนค่าหรือกำหนดการจัดแนวของเส้น. |
| [setAlignment(byte value)](#setAlignment-byte-) | คืนค่าหรือกำหนดการจัดแนวของเส้น. |
| [getJoinStyle()](#getJoinStyle--) | คืนค่าหรือกำหนดสไตล์การเชื่อมต่อของเส้น. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | คืนค่าหรือกำหนดสไตล์การเชื่อมต่อของเส้น. |
| [getMiterLimit()](#getMiterLimit--) | คืนค่าหรือกำหนดขีดจำกัด miter ของเส้น. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | คืนค่าหรือกำหนดขีดจำกัด miter ของเส้น. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดสิ้นสุดของเส้น. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดสิ้นสุดของเส้น. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดสิ้นสุดของเส้น. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | กำหนดว่าตัวอย่าง LineFormat สองตัวเท่ากันหรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบเส้นที่มีผลจริงพร้อมการสืบทอดที่ใช้. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

คืนค่า true หากรูปแบบของเส้นไม่ได้กำหนด (เป็นค่าเริ่มต้นเมื่อเพิ่งสร้าง) Boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

คืนค่ารูปแบบการเติมของเส้น. อ่านอย่างเดียว [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**คืนค่า:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

คืนค่ารูปแบบสเก็ตช์ของเส้น. อ่านอย่างเดียว [ISketchFormat](../../com.aspose.slides/isketchformat).

**คืนค่า:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

คืนค่าหรือกำหนดความกว้างของเส้น. อ่าน/เขียน double.

**คืนค่า:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

คืนค่าหรือกำหนดความกว้างของเส้น. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

คืนค่าหรือกำหนดสไตล์การขีดของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**คืนค่า:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์การขีดของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

คืนค่า หรือกำหนดรูปแบบการขีดแบบกำหนดเอง. อ่าน/เขียน float[].

**คืนค่า:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

คืนค่า หรือกำหนดรูปแบบการขีดแบบกำหนดเอง. อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

คืนค่าหรือกำหนดสไตล์การปลายเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**คืนค่า:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์การปลายเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

คืนค่าหรือกำหนดสไตล์ของเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**คืนค่า:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์ของเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

คืนค่าหรือกำหนดการจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**คืนค่า:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

คืนค่าหรือกำหนดการจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

คืนค่าหรือกำหนดสไตล์การเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**คืนค่า:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์การเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

คืนค่าหรือกำหนดขีดจำกัด miter ของเส้น. อ่าน/เขียน float.

**คืนค่า:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

คืนค่าหรือกำหนดขีดจำกัด miter ของเส้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

คืนค่าหรือกำหนดสไตล์หัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**คืนค่า:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์หัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

คืนค่าหรือกำหนดสไตล์หัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**คืนค่า:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

คืนค่าหรือกำหนดสไตล์หัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

คืนค่าหรือกำหนดความกว้างหัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**คืนค่า:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

คืนค่าหรือกำหนดความกว้างหัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

คืนค่าหรือกำหนดความกว้างหัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**คืนค่า:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

คืนค่าหรือกำหนดความกว้างหัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

คืนค่าหรือกำหนดความยาวหัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**คืนค่า:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

คืนค่าหรือกำหนดความยาวหัวศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

คืนค่าหรือกำหนดความยาวหัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**คืนค่า:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

คืนค่าหรือกำหนดความยาวหัวศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

กำหนดว่าตัวอย่าง LineFormat สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat ที่จะเปรียบเทียบกับ LineFormat ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก LineFormat ที่ระบุเท่ากับ LineFormat ปัจจุบัน; หากไม่เช่นนั้น, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบเส้นที่มีผลจริงพร้อมการสืบทอดที่ใช้.

**คืนค่า:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).