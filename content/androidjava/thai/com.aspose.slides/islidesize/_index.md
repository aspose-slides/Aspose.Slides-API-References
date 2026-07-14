---
title: ISlideSize
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนขนาดและการวางแนวของสไลด์.
type: docs
url: /th/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

แทนขนาดและการวางแนวของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSize()](#getSize--) | รับมิติของสไลด์ในหน่วยพอยต์ |
| [getType()](#getType--) | รับประเภทขนาดสไลด์ |
| [getOrientation()](#getOrientation--) | รับหรือกำหนดการวางแนวของสไลด์ |
| [setOrientation(int value)](#setOrientation-int-) | รับหรือกำหนดการวางแนวของสไลด์ |
| [setSize(int type, int scaleType)](#setSize-int-int-) | กำหนดขนาดสไลด์โดยประเภทและปรับขนาดเนื้อหาเดิม |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | กำหนดมิติของสไลด์อย่างชัดเจนและปรับขนาดเนื้อหาเดิม |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


รับมิติของสไลด์ในหน่วยพอยต์

--------------------

การกำหนดค่าใหม่จะรีเซ็ตคุณสมบัติ \#getType.getType ไปเป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)

**คืนค่า:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


รับประเภทขนาดสไลด์

--------------------

การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามมิติที่กำหนดไว้ล่วงหน้า โดยคงค่าการวางแนวปัจจุบันของ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)

**คืนค่า:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


รับหรือกำหนดการวางแนวของสไลด์

--------------------

การเปลี่ยนค่านี้จะสลับความกว้างและความสูงของสไลด์

**คืนค่า:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


รับหรือกำหนดการวางแนวของสไลด์

--------------------

การเปลี่ยนค่านี้จะสลับความกว้างและความสูงของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


กำหนดขนาดสไลด์โดยประเภทและปรับขนาดเนื้อหาเดิม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าเพื่อใช้ |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่ใช้ |

--------------------

การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) จะปรับ \#getSize.getSize ตามประเภทที่เลือก โดยคงค่าการวางแนวของ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


กำหนดมิติของสไลด์อย่างชัดเจนและปรับขนาดเนื้อหาเดิม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างของสไลด์ใหม่, หน่วยพอยต์ |
| height | float | ความสูงของสไลด์ใหม่, หน่วยพอยต์ |
| scaleType | int | โหมดการปรับขนาดเนื้อหาที่ใช้ |

--------------------

การรีเซ็ตนี้จะตั้งค่าคุณสมบัติ \#getType.getType ไปเป็น [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) และตั้งค่า \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |