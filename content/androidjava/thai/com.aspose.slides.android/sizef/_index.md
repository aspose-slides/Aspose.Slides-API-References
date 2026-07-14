---
title: SizeF
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: คลาสสำหรับอธิบายมิติของความกว้างและความสูงในหน่วยใดก็ได้โดยใช้ค่าแบบ floating-point.
type: docs
url: /th/com.aspose.slides.android/sizef/
---
**Inheritance:**
java.lang.Object
```
public class SizeF
```

คลาสสำหรับอธิบายมิติของความกว้างและความสูงในหน่วยใดก็ได้โดยใช้ค่าแบบ floating-point.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | สร้างอินสแตนซ์ SizeF ใหม่. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | รับค่า width ของขนาด. |
| [getHeight()](#getHeight--) | รับค่า height ของขนาด. |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่าขนาดนี้เท่ากับขนาดอื่นหรือไม่. |
| [hashCode()](#hashCode--) | {@inheritDoc} |
| [toString()](#toString--) | คืนค่าขนาดในรูปแบบสตริงที่มีรูปแบบ "WxH" |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

สร้างอินสแตนซ์ SizeF ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ค่าของ width ของขนาด |
| height | float | ค่าของ height ของขนาด |

### getWidth() {#getWidth--}
```
public float getWidth()
```

รับค่า width ของขนาด.

**ค่าที่คืน:**
float - width

### getHeight() {#getHeight--}
```
public float getHeight()
```

รับค่า height ของขนาด.

**ค่าที่คืน:**
float - height

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่าขนาดนี้เท่ากับขนาดอื่นหรือไม่.

สองขนาดเท่ากันก็ต่อเมื่อทั้งสองมี widths และ heights เดียวกัน.

For this purpose, the width/height float values are considered to be the same if and only if the method Float\#floatToIntBits(float).floatToIntBits(float) returns the identical  int  value when applied to each.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object |  |

**ค่าที่คืน:**
boolean - true  หากวัตถุเท่ากัน,  false  ในกรณีอื่น

### hashCode() {#hashCode--}
```
public int hashCode()
```

**ค่าที่คืน:**
int

### toString() {#toString--}
```
public String toString()
```

คืนค่าขนาดที่เป็นสตริงในรูปแบบ "WxH"

**ค่าที่คืน:**
java.lang.String - ตัวแทนสตริงของขนาด