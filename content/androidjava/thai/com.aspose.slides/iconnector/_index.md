---
title: IConnector
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงตัวเชื่อมต่อ.
type: docs
url: /th/com.aspose.slides/iconnector/
---
**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

เป็นตัวเชื่อมต่อ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | คืนค่า shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | คืนค่า Connector's locks. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดเริ่มต้นของ connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดเริ่มต้นของ connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดสิ้นสุดของ connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดสิ้นสุดของ connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สิ้นสุด. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สิ้นสุด. |
| [reroute()](#reroute--) | กำหนดเส้นทางใหม่ของ connector เพื่อให้ใช้เส้นทางสั้นที่สุดระหว่าง shapes ที่เชื่อมต่อ. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

คืนค่า shape's locks. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

คืนค่า Connector's locks. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดเริ่มต้นของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดเริ่มต้นของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดสิ้นสุดของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนด shape ที่จะเชื่อมต่อจุดสิ้นสุดของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. อ่าน/เขียน long.

**คืนค่า:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สิ้นสุด. อ่าน/เขียน long.

**คืนค่า:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สิ้นสุด. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

กำหนดเส้นทางใหม่ของ connector เพื่อให้ใช้เส้นทางสั้นที่สุดระหว่าง shapes ที่เชื่อมต่อ.