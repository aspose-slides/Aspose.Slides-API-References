---
title: IHtmlGenerator
second_title: Aspose.Slides สำหรับ Java API Reference
description: เครื่องสร้าง Html.
type: docs
url: /th/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

เครื่องสร้าง Html.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addHtml(char[] html)](#addHtml-char---) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | เพิ่มข้อความ HTML ที่จัดรูปแบบ |
| [addText(String text)](#addText-java.lang.String-) | เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addText(char[] text)](#addText-char---) | เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html |
| [getSlideImageSize()](#getSlideImageSize--) | คืนค่าขนาดภาพสไลด์ |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | คืนค่าหน่วยที่กำหนดขนาดภาพสไลด์ |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | คืนค่า css ของหน่วยที่กำหนดขนาดภาพสไลด์ |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | คืนดัชนีของสไลด์ที่เรนเดอร์ก่อนหน้า หรือ -1 หากเป็นสไลด์แรกที่กำลังเรนเดอร์ |
| [getSlideIndex()](#getSlideIndex--) | คืนดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่ |
| [getNextSlideIndex()](#getNextSlideIndex--) | คืนดัชนีของสไลด์ที่จะถูกเรนเดอร์หลังจากสไลด์ปัจจุบัน หรือ -1 หากกำลังเรนเดอร์สไลด์สุดท้าย |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | java.lang.String | ข้อความที่ต้องการเพิ่ม |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่ต้องการเพิ่ม |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่ต้องการเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html Linebreaks and whitespaces aren't replaced.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการเพิ่ม |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html Linebreaks and whitespaces aren't replaced.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่ต้องการเพิ่ม |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

เพิ่มข้อความธรรมดาไปยังไฟล์ html แทนที่อักขระพิเศษด้วยเอนทิตี html Linebreaks and whitespaces aren't replaced.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่ต้องการเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String | สตริงค่าแอตทริบิวต์ |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าแอตทริบิวต์ |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าแอตทริบิวต์ |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

คืนค่าขนาดภาพสไลด์ อ่านอย่างเดียว java.awt.geom.Dimension2D.

**คืนค่า:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

คืนค่าหน่วยที่กำหนดขนาดภาพสไลด์ อ่านอย่างเดียว [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**คืนค่า:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

คืนค่ารหัส CSS ของหน่วยที่กำหนดขนาดภาพสไลด์ อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

คืนดัชนีของสไลด์ที่เรนเดอร์ก่อนหน้า หรือ -1 หากเป็นสไลด์แรกที่กำลังเรนเดอร์ อ่านอย่างเดียว int.

**คืนค่า:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

คืนดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่ อ่านอย่างเดียว int.

**คืนค่า:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

คืนดัชนีของสไลด์ที่จะถูกเรนเดอร์หลังจากสไลด์ปัจจุบัน หรือ -1 หากกำลังเรนเดอร์สไลด์สุดท้าย อ่านอย่างเดียว int.

**คืนค่า:**
int