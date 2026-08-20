---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: แสดงขนาดและการจัดแนวของสไลด์
type: docs
url: /th/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

แสดงขนาดและการจัดแนวของสไลด์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSize()](#getSize--) | รับมิติของสไลด์ในหน่วยจุด |
| [getType()](#getType--) | รับประเภทขนาดสไลด์ |
| [getOrientation()](#getOrientation--) | รับหรือกำหนดการจัดแนวของสไลด์ |
| [setOrientation(int value)](#setOrientation-int-) | รับหรือกำหนดการจัดแนวของสไลด์ |
| [setSize(int type, int scaleType)](#setSize-int-int-) | ตั้งค่าขนาดสไลด์ตามประเภทและปรับขนาดเนื้อหาที่มีอยู่ |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | ตั้งค่ามิติของสไลด์โดยระบุโดยตรงและปรับขนาดเนื้อหาที่มีอยู่ |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


รับมิติของสไลด์ในหน่วยจุด

--------------------

การกำหนดค่าที่ใหม่จะรีเซ็ตคุณสมบัติ \#getType.getType ให้เป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)

**คืนค่า:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


รับประเภทขนาดสไลด์

--------------------

การกำหนดค่าที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามมิติที่กำหนดไว้ล่วงหน้า ในขณะที่คงค่าการจัดแนวปัจจุบันของ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)

**คืนค่า:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


รับหรือกำหนดการจัดแนวของสไลด์

--------------------

การเปลี่ยนค่าตัวนี้จะสลับความกว้างและความสูงของสไลด์

**คืนค่า:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


รับหรือกำหนดการจัดแนวของสไลด์

--------------------

การเปลี่ยนค่าตัวนี้จะสลับความกว้างและความสูงของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


ตั้งค่าขนาดสไลด์ตามประเภทและปรับขนาดเนื้อหาที่มีอยู่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ขนาดสไลด์ที่กำหนดล่วงหน้าที่จะใช้ |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่จะใช้ |

--------------------

การกำหนดค่าที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามประเภทที่เลือก ในขณะที่คงค่าการจัดแนวของ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


ตั้งค่ามิติของสไลด์โดยระบุโดยตรงและปรับขนาดเนื้อหาที่มีอยู่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างใหม่ของสไลด์, หน่วยเป็นจุด |
| height | float | ความสูงใหม่ของสไลด์, หน่วยเป็นจุด |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่จะใช้ |

--------------------

การกระทำนี้จะรีเซ็ตคุณสมบัติ \#getType.getType ให้เป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |