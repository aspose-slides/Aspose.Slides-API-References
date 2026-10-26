---
title: GeometryPath
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของเส้นทางเรขาคณิตของ GeometryShape
type: docs
url: /th/com.aspose.slides/geometrypath/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Represents geometry path of GeometryShape
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | สร้างอินสแตนซ์ของ GeometryPath |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPathData()](#getPathData--) | ส่งคืนเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง |
| [removeAt(int index)](#removeAt-int-) | ลบเซ็กเมนต์ที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [lineTo(float x, float y)](#lineTo-float-float-) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง |
| [closeFigure()](#closeFigure--) | ปิดรูปแบบปัจจุบันของเส้นทางนี้ |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | ตั้งค่าตำแหน่งจุดถัดไป |
| [moveTo(float x, float y)](#moveTo-float-float-) | ตั้งค่าตำแหน่งจุดถัดไป |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | ต่อส่วนโค้งที่ระบุเข้ากับเส้นทาง |
| [getFillMode()](#getFillMode--) | ตั้งค่าโหมดการเติม |
| [setFillMode(byte value)](#setFillMode-byte-) | ตั้งค่าโหมดการเติม |
| [getStroke()](#getStroke--) | ตั้งค่าลักษณะของขอบเส้น |
| [setStroke(boolean value)](#setStroke-boolean-) | ตั้งค่าลักษณะของขอบเส้น |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


สร้างอินสแตนซ์ของ GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


ส่งคืนเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง

**ส่งคืน:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบเซ็กเมนต์ที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเส้นทางเรขาคณิตที่ควรลบ. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```


เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | จุดสิ้นสุดของเส้น |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุดสิ้นสุดของเส้น |
| y | float | พิกัด Y ของจุดสิ้นสุดของเส้น |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```


เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทางแรก |
| point2 | android.graphics.PointF | จุดทิศทางที่สอง |
| point3 | android.graphics.PointF | จุดสิ้นสุด |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทางแรก |
| point2 | android.graphics.PointF | จุดทิศทางที่สอง |
| point3 | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```


เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทาง |
| point2 | android.graphics.PointF | จุดสิ้นสุด |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```


เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทาง |
| point2 | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของเซ็กเมนต์ใน PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


ปิดรูปแบบปัจจุบันของเส้นทางนี้

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```


ตั้งค่าตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | ตำแหน่งจุด |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


ตั้งค่าตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


ต่อส่วนโค้งที่ระบุเข้ากับเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างของสี่เหลี่ยม |
| heigth | float | ความสูงของสี่เหลี่ยม |
| startAngle | float | มุมเริ่มต้น |
| sweepAngle | float | มุมสวิง |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


ตั้งค่าโหมดการเติม

**ส่งคืน:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


ตั้งค่าโหมดการเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


ตั้งค่าลักษณะของขอบเส้น

**ส่งคืน:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


ตั้งค่าลักษณะของขอบเส้น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |