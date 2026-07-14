---
title: Connector
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงตัวเชื่อมต่อ.
type: docs
url: /th/com.aspose.slides/connector/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

เป็นตัวเชื่อมต่อ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | คืนค่า lock ของ shape. |
| [getConnectorLock()](#getConnectorLock--) | คืนค่า lock ของ connector. |
| [getShapeType()](#getShapeType--) | คืนค่า หรือกำหนดประเภท AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | คืนค่า หรือกำหนดประเภท AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนเริ่มต้นของ connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนเริ่มต้นของ connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนท้ายของ connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนท้ายของ connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ end shape. |
| [reroute()](#reroute--) | ปรับเส้นทาง connector เพื่อให้ใช้เส้นทางที่สั้นที่สุดระหว่าง shapes ที่เชื่อมต่อ |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

คืนค่า lock ของ shape. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

คืนค่า lock ของ connector. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

คืนค่า หรือกำหนดประเภท AutoShape. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**คืนค่า:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

คืนค่า หรือกำหนดประเภท AutoShape. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนเริ่มต้นของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนเริ่มต้นของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนท้ายของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนด shape ที่เชื่อมต่อส่วนท้ายของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ start shape. อ่าน/เขียน long.

**คืนค่า:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ start shape. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ end shape. อ่าน/เขียน long.

**คืนค่า:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของ connection site สำหรับ end shape. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

ปรับเส้นทาง connector เพื่อให้ใช้เส้นทางที่สั้นที่สุดระหว่าง shapes ที่เชื่อมต่อ.