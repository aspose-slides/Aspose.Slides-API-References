---
title: Connector
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงถึงตัวเชื่อมต่อ.
type: docs
url: /th/com.aspose.slides/connector/
---
**Inheritance:**  
การสืบทอด: java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ทำการใช้งานทั้งหมด: [com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

Represents a connector.  
แสดงถึงตัวเชื่อมต่อ.

## Methods  

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | คืนค่าการล็อกของรูปร่าง. |
| [getConnectorLock()](#getConnectorLock--) | คืนค่าการล็อกของตัวเชื่อมต่อ. |
| [getShapeType()](#getShapeType--) | คืนค่าหรือกำหนดประเภท AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | คืนค่าหรือกำหนดประเภท AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | คืนค่าหรือกำหนดรูปร่างที่เชื่อมต่อจุดเริ่มต้นของตัวเชื่อมต่อ. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่าหรือกำหนดรูปร่างที่เชื่อมต่อจุดเริ่มต้นของตัวเชื่อมต่อ. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | คืนค่าหรือกำหนดรูปร่างที่เชื่อมต่อจุดสิ้นสุดของตัวเชื่อมต่อ. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | คืนค่าหรือกำหนดรูปร่างที่เชื่อมต่อจุดสิ้นสุดของตัวเชื่อมต่อ. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | คืนค่า hoặcตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับรูปร่างเริ่มต้น. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | คืนค่า hoặcตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับรูปร่างเริ่มต้น. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | คืนค่า hoặcตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับรูปร่างสิ้นสุด. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | คืนค่า hoặcตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับรูปร่างสิ้นสุด. |
| [reroute()](#reroute--) | ปรับเส้นเชื่อมต่อใหม่เพื่อให้เส้นทางสั้นที่สุดระหว่างรูปร่างที่เชื่อมต่อ. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returns:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

คืนค่าการล็อกของตัวเชื่อมต่อ. อ่านอย่างเดียว [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returns:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

คืนค่า hoặcกำหนดประเภท AutoShape. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

คืนค่า hoặcกำหนดประเภท AutoShape. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

คืนค่า hoặcกำหนดรูปร่างที่เชื่อมต่อจุดเริ่มต้นของตัวเชื่อมต่อ. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**Returns:**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

คืนค่า hoặcกำหนดรูปร่างที่เชื่อมต่อจุดเริ่มต้นของตัวเชื่อมต่อ. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

คืนค่า hoặcกำหนดรูปร่างที่เชื่อมต่อจุดสิ้นสุดของตัวเชื่อมต่อ. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**Returns:**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

คืนค่า hoặcกำหนดรูปร่างที่เชื่อมต่อจุดสิ้นสุดของตัวเชื่อมต่อ. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

คืนค่า hoặcกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปร่างเริ่มต้น. อ่าน/เขียน long.

**Returns:**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

คืนค่า hoặcกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปร่างเริ่มต้น. อ่าน/เขียน long.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

คืนค่า hoặcกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปร่างสิ้นสุด. อ่าน/เขียน long.

**Returns:**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

คืนค่า hoặcกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปร่างสิ้นสุด. อ่าน/เขียน long.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

ปรับเส้นเชื่อมต่อใหม่เพื่อให้เส้นทางสั้นที่สุดระหว่างรูปร่างที่เชื่อมต่อ.