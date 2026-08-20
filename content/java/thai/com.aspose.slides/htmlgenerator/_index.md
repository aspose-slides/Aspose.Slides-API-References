---
title: HtmlGenerator
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เครื่องสร้าง Html.
type: docs
url: /th/com.aspose.slides/htmlgenerator/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

เครื่องสร้าง Html.
## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addHtml(char[] html)](#addHtml-char---) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addText(String text)](#addText-java.lang.String-) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addText(char[] text)](#addText-char---) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html |
| [getSlideImageSize()](#getSlideImageSize--) | คืนขนาดภาพสไลด์ |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | คืนหน่วยที่กำหนดขนาดภาพสไลด์ |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | คืนรหัส CSS ของหน่วยที่กำหนดขนาดภาพสไลด์ |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | คืนดัชนีของสไลด์ที่เรนเดอร์ก่อนหน้า หรือ -1 หากกำลังเรนเดอร์สไลด์แรก |
| [getSlideIndex()](#getSlideIndex--) | คืนดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่ |
| [getNextSlideIndex()](#getNextSlideIndex--) | คืนดัชนีของสไลด์ที่จะแสดงหลังสไลด์ปัจจุบัน หรือ -1 หากสไลด์ปัจจุบันเป็นสไลด์สุดท้าย |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| html | java.lang.String | ข้อความที่ต้องการเพิ่ม |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่ต้องการเพิ่ม |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่ต้องการเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html  บรรทัดใหม่และช่องว่างจะไม่ได้ถูกแทนที่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการเพิ่ม |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html  บรรทัดใหม่และช่องว่างจะไม่ได้ถูกแทนที่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่ต้องการเพิ่ม |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html  บรรทัดใหม่และช่องว่างจะไม่ได้ถูกแทนที่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่ต้องการเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String | สตริงค่าคุณลักษณะ |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าคุณลักษณะ |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าคุณลักษณะ |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

คืนขนาดภาพสไลด์  อ่านอย่างเดียว java.awt.geom.Dimension2D

**Returns:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

คืนหน่วยที่กำหนดขนาดภาพสไลด์  อ่านอย่างเดียว [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)

**Returns:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

คืนรหัส CSS ของหน่วยที่กำหนดขนาดภาพสไลด์  อ่านอย่างเดียว String

**Returns:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

คืนดัชนีของสไลด์ที่เรนเดอร์ก่อนหน้า หรือ -1 หากกำลังเรนเดอร์สไลด์แรก  อ่านอย่างเดียว int

**Returns:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

คืนดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่  อ่านอย่างเดียว int

**Returns:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

คืนดัชนีของสไลด์ที่จะแสดงหลังสไลด์ปัจจุบัน หรือ -1 หากสไลด์ปัจจุบันเป็นสไลด์สุดท้าย  อ่านอย่างเดียว int

**Returns:**
int