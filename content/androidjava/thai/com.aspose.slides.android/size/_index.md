---
title: Size
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คลาสสำหรับอธิบายมิติความกว้างและความสูงในหน่วยใดหน่วยหนึ่งที่กำหนดเอง.
type: docs
url: /th/com.aspose.slides.android/size/
---
**การสืบทอด:**
java.lang.Object
```
public class Size
```

คลาสสำหรับอธิบายมิติความกว้างและความสูงในหน่วยใดหน่วยหนึ่งที่กำหนดเอง
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | สร้างอินสแตนซ์ Size ใหม่ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | รับค่าความกว้างของขนาด |
| [getHeight()](#getHeight--) | รับค่าความสูงของขนาด |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่าขนาดนี้เท่ากับขนาดอื่นหรือไม่ |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | ส่งคืนขนาดในรูปแบบสตริงที่มีรูปแบบ "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


สร้างอินสแตนซ์ Size ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | int | ความกว้างของขนาด |
| height | int | ความสูงของขนาด |

### getWidth() {#getWidth--}
```
public int getWidth()
```


รับค่าความกว้างของขนาด

**ส่งคืน:**
int - ความกว้าง
### getHeight() {#getHeight--}
```
public int getHeight()
```


รับค่าความสูงของขนาด

**ส่งคืน:**
int - ความสูง
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


ตรวจสอบว่าขนาดนี้เท่ากับขนาดอื่นหรือไม่

สองขนาดเท่ากันก็ต่อเมื่อความกว้างและความสูงของทั้งสองเท่ากัน

อ็อบเจ็กต์ Size จะไม่เท่ากับอ็อบเจ็กต์ประเภทอื่นใดเลย

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object |  |

**ส่งคืน:**
boolean -  true  หากอ็อบเจ็กต์เท่ากัน,  false  มิฉะนั้น
### hashCode() {#hashCode--}
```
public int hashCode()
```




**ส่งคืน:**
int
### toString() {#toString--}
```
public String toString()
```


คืนค่าขนาดในรูปแบบสตริงที่มีรูปแบบ "WxH"

**ส่งคืน:**
java.lang.String - การแสดงผลของขนาดในรูปแบบสตริง