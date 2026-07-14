---
title: LineFormat
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงรูปแบบของเส้น.
type: docs
url: /th/com.aspose.slides/lineformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

แสดงถึงรูปแบบของเส้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | คืนค่า true หากรูปแบบของเส้นไม่ได้กำหนด (เช่นเมื่อเพิ่งสร้าง, ค่าเริ่มต้น) |
| [getFillFormat()](#getFillFormat--) | คืนค่ารูปแบบการเติมของเส้น. |
| [getSketchFormat()](#getSketchFormat--) | คืนค่ารูปแบบสเก็ตช์ของเส้น. |
| [getWidth()](#getWidth--) | คืนค่า หรือกำหนด ความกว้างของเส้น. |
| [setWidth(double value)](#setWidth-double-) | คืนค่า หรือกำหนด ความกว้างของเส้น. |
| [getDashStyle()](#getDashStyle--) | คืนค่า หรือกำหนด รูปแบบจังหวะของเส้น. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | คืนค่า หรือกำหนด รูปแบบจังหวะของเส้น. |
| [getCustomDashPattern()](#getCustomDashPattern--) | คืนค่า หรือกำหนด รูปแบบจังหวะที่กำหนดเอง. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | คืนค่า หรือกำหนด รูปแบบจังหวะที่กำหนดเอง. |
| [getCapStyle()](#getCapStyle--) | คืนค่า หรือกำหนด สไตล์ของปลายเส้น. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | คืนค่า หรือกำหนด สไตล์ของปลายเส้น. |
| [getStyle()](#getStyle--) | คืนค่า หรือกำหนด สไตล์ของเส้น. |
| [setStyle(byte value)](#setStyle-byte-) | คืนค่า หรือกำหนด สไตล์ของเส้น. |
| [getAlignment()](#getAlignment--) | คืนค่า หรือกำหนด การจัดแนวของเส้น. |
| [setAlignment(byte value)](#setAlignment-byte-) | คืนค่า หรือกำหนด การจัดแนวของเส้น. |
| [getJoinStyle()](#getJoinStyle--) | คืนค่า หรือกำหนด สไตล์การเชื่อมต่อของเส้น. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | คืนค่า หรือกำหนด สไตล์การเชื่อมต่อของเส้น. |
| [getMiterLimit()](#getMiterLimit--) | คืนค่า หรือกำหนด ขีดจำกัดมิตเตอร์ของเส้น. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | คืนค่า หรือกำหนด ขีดจำกัดมิตเตอร์ของเส้น. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดสิ้นสุดของเส้น. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | กำหนดว่าตัวอย่าง LineFormat ทั้งสองเท่ากันหรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการกำหนดรูปแบบเส้นที่มีผลโดยใช้การสืบทอด. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object |  |

**คืนค่า:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

คืนค่า true หากรูปแบบของเส้นไม่ได้กำหนด (เช่นเมื่อเพิ่งสร้าง, ค่าเริ่มต้น) อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

คืนค่ารูปแบบการเติมของเส้น. อ่านอย่างเดียว [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**คืนค่า:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

คืนค่ารูปแบบสเก็ตช์ของเส้น. อ่านอย่างเดียว [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**คืนค่า:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

คืนค่า หรือกำหนด ความกว้างของเส้น. อ่าน/เขียน double .

**คืนค่า:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

คืนค่า หรือกำหนด ความกว้างของเส้น. อ่าน/เขียน double .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

คืนค่า หรือกำหนด รูปแบบจังหวะของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**คืนค่า:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

คืนค่า หรือกำหนด รูปแบบจังหวะของเส้น. อ่าน/เขียน [LineDashStyle](../../com.aspose.slides/linedashstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

คืนค่า หรือกำหนด รูปแบบจังหวะที่กำหนดเอง. อ่าน/เขียน float[] .

**คืนค่า:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

คืนค่า หรือกำหนด รูปแบบจังหวะที่กำหนดเอง. อ่าน/เขียน float[] .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

คืนค่า หรือกำหนด สไตล์ของปลายเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**คืนค่า:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

คืนค่า หรือกำหนด สไตล์ของปลายเส้น. อ่าน/เขียน [LineCapStyle](../../com.aspose.slides/linecapstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

คืนค่า หรือกำหนด สไตล์ของเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**คืนค่า:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

คืนค่า หรือกำหนด สไตล์ของเส้น. อ่าน/เขียน [LineStyle](../../com.aspose.slides/linestyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

คืนค่า หรือกำหนด การจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**คืนค่า:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

คืนค่า หรือกำหนด การจัดแนวของเส้น. อ่าน/เขียน [LineAlignment](../../com.aspose.slides/linealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

คืนค่า หรือกำหนด สไตล์การเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**คืนค่า:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

คืนค่า หรือกำหนด สไตล์การเชื่อมต่อของเส้น. อ่าน/เขียน [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

คืนค่า หรือกำหนด ขีดจำกัดมิตเตอร์ของเส้น. อ่าน/เขียน float .

**คืนค่า:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

คืนค่า หรือกำหนด ขีดจำกัดมิตเตอร์ของเส้น. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**คืนค่า:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**คืนค่า:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

คืนค่า หรือกำหนด สไตล์หัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**คืนค่า:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**คืนค่า:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

คืนค่า หรือกำหนด ความกว้างของหัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**คืนค่า:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**คืนค่า:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

คืนค่า หรือกำหนด ความยาวของหัวลูกศรที่จุดสิ้นสุดของเส้น. อ่าน/เขียน [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

กำหนดว่าตัวอย่าง LineFormat ทั้งสองเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat ที่จะเปรียบเทียบกับ LineFormat ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก LineFormat ที่ระบุเท่ากับ LineFormat ปัจจุบัน; มิฉะนั้น, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

รับข้อมูลการกำหนดรูปแบบเส้นที่มีผลโดยใช้การสืบทอด.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - หนึ่ง [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).