---
title: SlideSize
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงขนาดและการวางแนวของสไลด์.
type: docs
url: /th/com.aspose.slides/slidesize/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

แสดงถึงขนาดและการวางแนวของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSize()](#getSize--) | รับขนาดของสไลด์ในหน่วยจุด. |
| [getType()](#getType--) | รับประเภทขนาดสไลด์. |
| [getOrientation()](#getOrientation--) | รับหรือกำหนดการวางแนวของสไลด์. |
| [setOrientation(int value)](#setOrientation-int-) | รับหรือกำหนดการวางแนวของสไลด์. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | ตั้งค่าขนาดสไลด์ตามประเภทและปรับสเกลเนื้อหาที่มีอยู่. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | ตั้งค่าขนาดสไลด์โดยกำหนดอย่างชัดเจนและปรับสเกลเนื้อหาที่มีอยู่. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


รับขนาดของสไลด์ในหน่วยจุด.

--------------------

การกำหนดค่าที่ใหม่จะรีเซ็ตคุณสมบัติ \#getType.getType ไปเป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**คืนค่า:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


รับประเภทขนาดสไลด์.

--------------------

การกำหนดค่าที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามมิติที่กำหนดไว้ล่วงหน้า ในขณะที่คงค่าการวางแนวปัจจุบันของ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**คืนค่า:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


รับหรือกำหนดการวางแนวของสไลด์.

--------------------

การเปลี่ยนค่านี้จะสลับความกว้างและความสูงของสไลด์.

**คืนค่า:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


รับหรือกำหนดการวางแนวของสไลด์.

--------------------

การเปลี่ยนค่านี้จะสลับความกว้างและความสูงของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


ตั้งค่าขนาดสไลด์ตามประเภทและปรับสเกลเนื้อหาที่มีอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าที่จะใช้. |
| scaleType | int | โหมดการปรับสเกลเนื้อหาที่จะใช้. |

--------------------

การกำหนดค่าที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามประเภทที่เลือกไว้ ในขณะที่รักษาการวางแนวใน \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ไว้.

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


ตั้งค่าขนาดสไลด์โดยกำหนดอย่างชัดเจนและปรับสเกลเนื้อหาที่มีอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างใหม่ของสไลด์เป็นหน่วยจุด. |
| height | float | ความสูงใหม่ของสไลด์เป็นหน่วยจุด. |
| scaleType | int | โหมดการปรับสเกลเนื้อหาที่จะใช้. |

--------------------

นี่จะรีเซ็ตคุณสมบัติ \#getType.getType ไปเป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).