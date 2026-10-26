---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /th/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

แสดงเส้นทางเรขาคณิตของ GeometryShape
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPathData()](#getPathData--) | ส่งคืนเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง |
| [removeAt(int index)](#removeAt-int-) | ลบส่วนที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [lineTo(float x, float y)](#lineTo-float-float-) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ตำแหน่งที่ระบุของเส้นทาง |
| [closeFigure()](#closeFigure--) | ปิดรูปทรงปัจจุบันของเส้นทางนี้ |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | กำหนดตำแหน่งจุดถัดไป |
| [moveTo(float x, float y)](#moveTo-float-float-) | กำหนดตำแหน่งจุดถัดไป |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | เพิ่มส่วนโค้งที่ระบุลงในเส้นทาง |
| [getFillMode()](#getFillMode--) | กำหนดโหมดการเติม |
| [setFillMode(byte value)](#setFillMode-byte-) | กำหนดโหมดการเติม |
| [getStroke()](#getStroke--) | กำหนดลักษณะการขีดเส้น |
| [setStroke(boolean value)](#setStroke-boolean-) | กำหนดลักษณะการขีดเส้น |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


ส่งคืนเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง

**ส่งคืน:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบส่วนที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของส่วนของเส้นทางที่ต้องการลบ |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | จุดสิ้นสุดของเส้น |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุดสิ้นสุดของเส้น |
| y | float | พิกัด Y ของจุดสิ้นสุดของเส้น |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |
| index | long | ดัชนีของส่วนใน PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทางแรก |
| point2 | android.graphics.PointF | จุดทิศทางที่สอง |
| point3 | android.graphics.PointF | จุดสิ้นสุด |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทางแรก |
| point2 | android.graphics.PointF | จุดทิศทางที่สอง |
| point3 | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทาง |
| point2 | android.graphics.PointF | จุดสิ้นสุด |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | android.graphics.PointF | จุดทิศทาง |
| point2 | android.graphics.PointF | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


เพิ่มเส้นโค้ง Bezier แบบควอดราติกที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


ปิดรูปทรงปัจจุบันของเส้นทางนี้

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


กำหนดตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | android.graphics.PointF | ตำแหน่งจุด |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


กำหนดตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


เพิ่มส่วนโค้งที่ระบุลงในเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างของสี่เหลี่ยม |
| heigth | float | ความสูงของสี่เหลี่ยม |
| startAngle | float | มุมเริ่มต้น |
| sweepAngle | float | มุมสวีป |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


กำหนดโหมดการเติม

**ส่งคืน:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


กำหนดโหมดการเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


กำหนดลักษณะการขีดเส้น

**ส่งคืน:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


กำหนดลักษณะการขีดเส้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |