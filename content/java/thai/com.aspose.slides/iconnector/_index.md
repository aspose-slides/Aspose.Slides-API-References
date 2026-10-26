---
title: IConnector
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: แสดงถึงตัวเชื่อม.
type: docs
url: /th/com.aspose.slides/iconnector/
---
**ทุกอินเทอร์เฟซที่ทำการ Implement:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Represents a connector.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | คืนค่าล็อกของรูปร่าง. |
| [getConnectorLock()](#getConnectorLock--) | คืนค่าล็อกของ Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนเริ่มของ connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนเริ่มของ connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนท้ายของ connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนท้ายของ connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างเริ่มต้น. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างเริ่มต้น. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างสิ้นสุด. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างสิ้นสุด. |
| [reroute()](#reroute--) | กำหนดเส้นทางใหม่ของ connector เพื่อให้เป็นเส้นทางสั้นที่สุดระหว่างรูปร่างที่เชื่อมต่อ |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

คืนค่าล็อกของรูปร่าง. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

คืนค่าล็อกของ Connector. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**คืนค่า:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนเริ่มของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนเริ่มของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนท้ายของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

คืนค่า หรือกำหนดรูปร่างที่เชื่อมต่อส่วนท้ายของ connector. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างเริ่มต้น. อ่าน/เขียน long.

**คืนค่า:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างเริ่มต้น. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างสิ้นสุด. อ่าน/เขียน long.

**คืนค่า:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

คืนค่า หรือกำหนดดัชนีของตำแหน่งเชื่อมต่อสำหรับรูปร่างสิ้นสุด. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

กำหนดเส้นทางใหม่ของ connector เพื่อให้เป็นเส้นทางสั้นที่สุดระหว่างรูปร่างที่เชื่อมต่อ.