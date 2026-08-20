---
title: GeometryPath
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงเส้นทางเรขาคณิตของ GeometryShape
type: docs
url: /th/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

แสดงถึงเส้นทางเรขาคณิตของ GeometryShape
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | สร้างอินสแตนซ์ของ GeometryPath |
## เมธอด

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | คืนค่าเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง |
| [removeAt(int index)](#removeAt-int-) | ลบส่วนที่ตำแหน่ง index ที่ระบุของเส้นทางเรขาคณิต |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [lineTo(float x, float y)](#lineTo-float-float-) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | เพิ่มเส้นโค้ง Bezier cubic ที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier cubic ที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นโค้ง Bezier cubic ไปยังตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier cubic ไปยังตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | เพิ่มเส้นโค้ง Bezier quadratic ที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier quadratic ที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นโค้ง Bezier quadratic ไปยังตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier quadratic ไปยังตำแหน่งที่ระบุของเส้นทาง |
| [closeFigure()](#closeFigure--) | ปิดรูปแบบปัจจุบันของเส้นทางนี้ |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | ตั้งตำแหน่งจุดถัดไป |
| [moveTo(float x, float y)](#moveTo-float-float-) | ตั้งตำแหน่งจุดถัดไป |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | ผนวกโค้งที่ระบุไปยังเส้นทาง |
| [getFillMode()](#getFillMode--) | ตั้งโหมดการเติม |
| [setFillMode(byte value)](#setFillMode-byte-) | ตั้งโหมดการเติม |
| [getStroke()](#getStroke--) | ตั้งลักษณะการเส้นขอบ |
| [setStroke(boolean value)](#setStroke-boolean-) | ตั้งลักษณะการเส้นขอบ |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

สร้างอินสแตนซ์ของ GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

คืนค่าเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง

**คืนค่า:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบส่วนที่ตำแหน่ง index ที่ระบุของเส้นทางเรขาคณิต

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของส่วนในเส้นทางที่ต้องการลบ |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | จุดสิ้นสุดของเส้นตรง |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของจุดสิ้นสุดของเส้นตรง |
| y | float | พิกัด Y ของจุดสิ้นสุดของเส้นตรง |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

เพิ่มเส้นตรงไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |
| index | long | ดัชนีของส่วนใน PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

เพิ่มเส้นโค้ง Bezier cubic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทางแรก |
| point2 | java.awt.geom.Point2D.Float | จุดทิศทางที่สอง |
| point3 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

เพิ่มเส้นโค้ง Bezier cubic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

เพิ่มเส้นโค้ง Bezier cubic ไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทางแรก |
| point2 | java.awt.geom.Point2D.Float | จุดทิศทางที่สอง |
| point3 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

เพิ่มเส้นโค้ง Bezier cubic ไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

เพิ่มเส้นโค้ง Bezier quadratic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทาง |
| point2 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

เพิ่มเส้นโค้ง Bezier quadratic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

เพิ่มเส้นโค้ง Bezier quadratic ไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทาง |
| point2 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

เพิ่มเส้นโค้ง Bezier quadratic ไปยังตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของส่วนใน PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

ปิดรูปแบบปัจจุบันของเส้นทางนี้

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

ตั้งตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | ตำแหน่งจุด |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

ตั้งตำแหน่งจุดถัดไป

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

ผนวกโค้งที่ระบุไปยังเส้นทาง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | ความกว้างของสี่เหลี่ยม |
| heigth | float | ความสูงของสี่เหลี่ยม |
| startAngle | float | มุมเริ่มต้น |
| sweepAngle | float | มุมการสวิง |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

ตั้งโหมดการเติม

**คืนค่า:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

ตั้งโหมดการเติม

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

ตั้งลักษณะการเส้นขอบ

**คืนค่า:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

ตั้งลักษณะการเส้นขอบ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |