---
title: Connector
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả một connector.
type: docs
url: /vi/com.aspose.slides/connector/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Mô tả một connector.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Trả về khóa của shape. |
| [getConnectorLock()](#getConnectorLock--) | Trả về khóa của connector. |
| [getShapeType()](#getShapeType--) | Trả về hoặc đặt kiểu AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Trả về hoặc đặt kiểu AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Trả về hoặc đặt shape để gắn đầu đầu của connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc đặt shape để gắn đầu đầu của connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Trả về hoặc đặt shape để gắn cuối của connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc đặt shape để gắn cuối của connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape bắt đầu. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape bắt đầu. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape kết thúc. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape kết thúc. |
| [reroute()](#reroute--) | Định tuyến lại connector sao cho nó đi theo đường ngắn nhất có thể giữa các shape mà nó kết nối. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Trả về khóa của shape. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Trả về khóa của connector. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Trả về hoặc đặt kiểu AutoShape. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Trả về:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Trả về hoặc đặt kiểu AutoShape. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Trả về hoặc đặt shape để gắn đầu đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Trả về hoặc đặt shape để gắn đầu đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Trả về hoặc đặt shape để gắn cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Trả về hoặc đặt shape để gắn cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape bắt đầu. Đọc/ghi long.

**Trả về:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape bắt đầu. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape kết thúc. Đọc/ghi long.

**Trả về:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape kết thúc. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Định tuyến lại connector sao cho nó đi theo đường ngắn nhất có thể giữa các shape mà nó kết nối.