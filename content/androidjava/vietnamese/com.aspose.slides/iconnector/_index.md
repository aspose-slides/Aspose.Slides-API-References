---
title: IConnector
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một connector.
type: docs
url: /vi/com.aspose.slides/iconnector/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Biểu diễn một connector.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Trả về khóa của shape. |
| [getConnectorLock()](#getConnectorLock--) | Trả về khóa của Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Trả về hoặc đặt shape để gắn đầu của connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc đặt shape để gắn đầu của connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Trả về hoặc đặt shape để gắn cuối của connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc đặt shape để gắn cuối của connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Trả về hoặc đặt chỉ mục của điểm kết nối cho shape bắt đầu. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Trả về hoặc đặt chỉ mục của điểm kết nối cho shape bắt đầu. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Trả về hoặc đặt chỉ mục của điểm kết nối cho shape kết thúc. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Trả về hoặc đặt chỉ mục của điểm kết nối cho shape kết thúc. |
| [reroute()](#reroute--) | Định lại connector sao cho nó lấy đường ngắn nhất có thể giữa các shape mà nó kết nối. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Trả về khóa của shape. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Trả về khóa của Connector. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Trả về hoặc đặt shape để gắn đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Trả về hoặc đặt shape để gắn đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Trả về hoặc đặt shape để gắn cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Trả về hoặc đặt shape để gắn cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Trả về hoặc đặt chỉ mục của điểm kết nối cho shape bắt đầu. Đọc/ghi long.

**Trả về:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Trả về hoặc đặt chỉ mục của điểm kết nối cho shape bắt đầu. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Trả về hoặc đặt chỉ mục của điểm kết nối cho shape kết thúc. Đọc/ghi long.

**Trả về:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Trả về hoặc đặt chỉ mục của điểm kết nối cho shape kết thúc. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Định lại connector sao cho nó lấy đường ngắn nhất có thể giữa các shape mà nó kết nối.