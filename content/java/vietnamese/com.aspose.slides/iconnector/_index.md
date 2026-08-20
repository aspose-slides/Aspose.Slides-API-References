---
title: IConnector
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả một connector.
type: docs
url: /vi/com.aspose.slides/iconnector/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Mô tả một connector.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Trả về các khóa của shape. |
| [getConnectorLock()](#getConnectorLock--) | Trả về các khóa của Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Trả về hoặc thiết lập shape để gắn phần đầu của connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc thiết lập shape để gắn phần đầu của connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Trả về hoặc thiết lập shape để gắn phần cuối của connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Trả về hoặc thiết lập shape để gắn phần cuối của connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape bắt đầu. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape bắt đầu. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape kết thúc. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape kết thúc. |
| [reroute()](#reroute--) | Điều hướng lại connector sao cho nó đi theo đường ngắn nhất có thể giữa các shape mà nó kết nối. |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Trả về các khóa của shape. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Trả về các khóa của Connector. Chỉ đọc [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Trả về:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Trả về hoặc thiết lập shape để gắn phần đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Trả về hoặc thiết lập shape để gắn phần đầu của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Trả về hoặc thiết lập shape để gắn phần cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Trả về hoặc thiết lập shape để gắn phần cuối của connector. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape bắt đầu. Đọc/ghi long.

**Trả về:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape bắt đầu. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape kết thúc. Đọc/ghi long.

**Trả về:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Trả về hoặc thiết lập chỉ mục của vị trí kết nối cho shape kết thúc. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

Điều hướng lại connector sao cho nó đi theo đường ngắn nhất có thể giữa các shape mà nó kết nối.