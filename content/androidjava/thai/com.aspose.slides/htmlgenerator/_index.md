---
title: HtmlGenerator
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: ตัวสร้าง Html.
type: docs
url: /th/com.aspose.slides/htmlgenerator/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)  
```
public final class HtmlGenerator implements IHtmlGenerator
```

ตัวสร้าง HTML.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | เพิ่มข้อความ HTML ที่จัดรูปแบบไว้ |
| [addHtml(char[] html)](#addHtml-char---) | เพิ่มข้อความ HTML ที่จัดรูปแบบไว้ |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | เพิ่มข้อความ HTML ที่จัดรูปแบบไว้ |
| [addText(String text)](#addText-java.lang.String-) | เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML |
| [addText(char[] text)](#addText-char---) | เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML |
| [getSlideImageSize()](#getSlideImageSize--) | ส่งคืนขนาดของภาพสไลด์ |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | ส่งคืนหน่วยที่ใช้กำหนดขนาดภาพสไลด์ |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | ส่งคืนรหัส CSS ของหน่วยที่ใช้กำหนดขนาดภาพสไลด์ |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | ส่งคืนดัชนีของสไลด์ที่แสดงผลก่อนหน้า หรือ -1 หากเป็นสไลด์แรกที่กำลังแสดงผล |
| [getSlideIndex()](#getSlideIndex--) | ส่งคืนดัชนีของสไลด์ที่กำลังแสดงผลอยู่ |
| [getNextSlideIndex()](#getNextSlideIndex--) | ส่งคืนดัชนีของสไลด์ที่จะแสดงผลถัดจากสไลด์ปัจจุบัน หรือ -1 หากกำลังแสดงผลสไลด์สุดท้าย |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | java.lang.String | ข้อความที่จะเพิ่ม |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่จะเพิ่ม |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

เพิ่มข้อความ HTML ที่จัดรูปแบบไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| html | char[] | ข้อความที่จะเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. ไม่เปลี่ยนบรรทัดใหม่และช่องว่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะเพิ่ม |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. ไม่เปลี่ยนบรรทัดใหม่และช่องว่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่จะเพิ่ม |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

เพิ่มข้อความธรรมดาในไฟล์ HTML โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. ไม่เปลี่ยนบรรทัดใหม่และช่องว่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | char[] | ข้อความที่จะเพิ่ม |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String | สตริงค่าคุณลักษณะ |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าคุณลักษณะ |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

ใส่เครื่องหมายอัญประกาศให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ HTML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char[] | สตริงค่าคุณลักษณะ |
| startIndex | int | ดัชนีเริ่มต้นของส่วนที่ต้องการเพิ่ม |
| length | int | ความยาวของส่วนที่ต้องการเพิ่ม |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

ส่งคืนขนาดของภาพสไลด์. อ่านอย่างเดียว [SizeF](../../com.aspose.slides.android/sizef).

**ส่งคืน:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

ส่งคืนหน่วยที่ใช้กำหนดขนาดภาพสไลด์. อ่านอย่างเดียว [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**ส่งคืน:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

ส่งคืนรหัส CSS ของหน่วยที่ใช้กำหนดขนาดภาพสไลด์. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

ส่งคืนดัชนีของสไลด์ที่แสดงผลก่อนหน้า หรือ -1 หากเป็นสไลด์แรกที่กำลังแสดงผล. อ่านอย่างเดียว int.

**ส่งคืน:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

ส่งคืนดัชนีของสไลด์ที่กำลังแสดงผลอยู่. อ่านอย่างเดียว int.

**ส่งคืน:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

ส่งคืนดัชนีของสไลด์ที่จะแสดงผลถัดจากสไลด์ปัจจุบัน หรือ -1 หากกำลังแสดงผลสไลด์สุดท้าย. อ่านอย่างเดียว int.

**ส่งคืน:**
int