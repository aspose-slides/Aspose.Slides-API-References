---
title: SlideSize
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงขนาดและการวางแนวของสไลด์.
type: docs
url: /th/com.aspose.slides/slidesize/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

แสดงถึงขนาดและการวางแนวของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSize()](#getSize--) | รับค่ามิติของสไลด์เป็นจุด. |
| [getType()](#getType--) | รับประเภทขนาดของสไลด์. |
| [getOrientation()](#getOrientation--) | รับหรือกำหนดการวางแนวของสไลด์. |
| [setOrientation(int value)](#setOrientation-int-) | รับหรือกำหนดการวางแนวของสไลด์. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | กำหนดขนาดสไลด์ตามประเภทและปรับขนาดเนื้อหาที่มีอยู่. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | กำหนดมิติของสไลด์โดยเจาะจงและปรับขนาดเนื้อหาที่มีอยู่. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


รับค่ามิติของสไลด์เป็นจุด.

--------------------

การกำหนดค่าใหม่จะรีเซ็ตคุณสมบัติ \#getType.getType ไปยัง [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**คืนค่า:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


รับประเภทขนาดของสไลด์.

--------------------

การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามมิติที่กำหนดไว้ล่วงหน้า ในขณะที่ยังคงรักษา \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ไว้.

**คืนค่า:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


รับหรือกำหนดการวางแนวของสไลด์.

--------------------

การเปลี่ยนค่าที่นี้จะสลับความกว้างและความสูงของสไลด์.

**คืนค่า:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


รับหรือกำหนดการวางแนวของสไลด์.

--------------------

การเปลี่ยนค่าที่นี้จะสลับความกว้างและความสูงของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


กำหนดขนาดสไลด์ตามประเภทและปรับขนาดเนื้อหาที่มีอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าเพื่อใช้. |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่จะใช้. |

--------------------

การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามประเภทที่เลือก ในขณะที่ยังคงรักษา \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ไว้. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


กำหนดมิติของสไลด์โดยเจาะจงและปรับขนาดเนื้อหาที่มีอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างใหม่ของสไลด์, หน่วยเป็นจุด. |
| height | float | ความสูงใหม่ของสไลด์, หน่วยเป็นจุด. |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่จะใช้. |

--------------------

การรีเซ็ตนี้จะตั้งค่า \#getType.getType ไปยัง [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |