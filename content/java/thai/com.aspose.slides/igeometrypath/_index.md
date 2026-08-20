---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: แทนเส้นทางเรขาคณิตของ GeometryShape
type: docs
url: /th/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

แทนเส้นทางเรขาคณิตของ GeometryShape
## วิธีการ

| Method | คำอธิบาย |
| --- | --- |
| [getPathData()](#getPathData--) | คืนค่าเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของเซกเมนต์เส้นทาง. |
| [removeAt(int index)](#removeAt-int-) | ลบเซกเมนต์ที่ตำแหน่งที่ระบุของเส้นทางเรขาคณิต. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [lineTo(float x, float y)](#lineTo-float-float-) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ส่วนท้ายของเส้นทาง |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [closeFigure()](#closeFigure--) | ปิดรูปแบบปัจจุบันของเส้นทางนี้ |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | ตั้งค่าตำแหน่งจุดถัดไป. |
| [moveTo(float x, float y)](#moveTo-float-float-) | ตั้งค่าตำแหน่งจุดถัดไป. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | เพิ่มโค้งที่ระบุลงในเส้นทาง. |
| [getFillMode()](#getFillMode--) | ตั้งค่าโหมดการเติม |
| [setFillMode(byte value)](#setFillMode-byte-) | ตั้งค่าโหมดการเติม |
| [getStroke()](#getStroke--) | ตั้งค่าการปรากฏของเส้นขอบ |
| [setStroke(boolean value)](#setStroke-boolean-) | ตั้งค่าการปรากฏของเส้นขอบ |

### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

คืนค่าเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของเซกเมนต์เส้นทาง.

**คืนค่า:**  
com.aspose.slides.IPathSegment[]

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบเซกเมนต์ที่ตำแหน่งที่ระบุของเส้นทางเรขาคณิต.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเส้นทางเรขาคณิตที่ควรลบ. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | จุดสิ้นสุดของเส้น |

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

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของเซกเมนต์ใน PathData |

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
| index | long | ดัชนีของเซกเมนต์ใน PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทางแรก |
| point2 | java.awt.geom.Point2D.Float | จุดทิศทางที่สอง |
| point3 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทางแรก |
| point2 | java.awt.geom.Point2D.Float | จุดทิศทางที่สอง |
| point3 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของเซกเมนต์ใน PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทางแรก |
| y1 | float | พิกัด Y ของจุดทิศทางแรก |
| x2 | float | พิกัด X ของจุดทิศทางที่สอง |
| y2 | float | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | float | พิกัด X ของจุดสิ้นสุด |
| y3 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของเซกเมนต์ใน PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทาง |
| point2 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ส่วนท้ายของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | จุดทิศทาง |
| point2 | java.awt.geom.Point2D.Float | จุดสิ้นสุด |
| index | long | ดัชนีของเซกเมนต์ใน PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

เพิ่มเส้นโค้ง Bezier แบบ quadratic ที่ตำแหน่งที่ระบุของเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x1 | float | พิกัด X ของจุดทิศทาง |
| y1 | float | พิกัด Y ของจุดทิศทาง |
| x2 | float | พิกัด X ของจุดสิ้นสุด |
| y2 | float | พิกัด Y ของจุดสิ้นสุด |
| index | long | ดัชนีของเซกเมนต์ใน PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

ปิดรูปแบบปัจจุบันของเส้นทางนี้

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

ตั้งค่าตำแหน่งจุดถัดไป.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | ตำแหน่งของจุด |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

ตั้งค่าตำแหน่งจุดถัดไป.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของจุด |
| y | float | พิกัด Y ของจุด |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

เพิ่มโค้งที่ระบุลงในเส้นทาง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | float | ความกว้างของสี่เหลี่ยม |
| heigth | float | ความสูงของสี่เหลี่ยม |
| startAngle | float | มุมเริ่มต้น |
| sweepAngle | float | มุมการสวิง |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

ตั้งค่าโหมดการเติม

**คืนค่า:**  
byte

### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

ตั้งค่าโหมดการเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

ตั้งค่าการปรากฏของเส้นขอบ

**คืนค่า:**  
boolean

### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

ตั้งค่าการปรากฏของเส้นขอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |