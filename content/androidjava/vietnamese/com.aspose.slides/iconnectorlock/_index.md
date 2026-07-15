---
title: IConnectorLock
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Xác định các thao tác nào bị vô hiệu trên Connector cha.
type: docs
url: /vi/com.aspose.slides/iconnectorlock/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

Xác định các thao tác nào bị vô hiệu trên Connector cha.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Xác định xem việc thêm hình này vào nhóm có bị cấm hay không. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Xác định xem việc thêm hình này vào nhóm có bị cấm hay không. |
| [getSelectLocked()](#getSelectLocked--) | Xác định xem việc chọn hình này có bị cấm hay không. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Xác định xem việc chọn hình này có bị cấm hay không. |
| [getRotateLocked()](#getRotateLocked--) | Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [getPositionMove()](#getPositionMove--) | Xác định xem việc di chuyển hình này có bị cấm hay không. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | Xác định xem việc di chuyển hình này có bị cấm hay không. |
| [getSizeLocked()](#getSizeLocked--) | Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Xác định xem việc thay đổi trực tiếp dạng nét viền của hình này có bị cấm hay không. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Xác định xem việc thay đổi trực tiếp dạng nét viền của hình này có bị cấm hay không. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Xác định xem việc thay đổi mũi tên có bị cấm hay không. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Xác định xem việc thay đổi mũi tên có bị cấm hay không. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Xác định xem việc thay đổi loại hình có bị cấm hay không. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Xác định xem việc thay đổi loại hình có bị cấm hay không. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Xác định xem việc thêm hình này vào nhóm có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Xác định xem việc thêm hình này vào nhóm có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Xác định xem việc chọn hình này có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Xác định xem việc chọn hình này có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

Xác định xem việc di chuyển hình này có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

Xác định xem việc di chuyển hình này có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Xác định xem việc thay đổi trực tiếp dạng nét viền của hình này có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Xác định xem việc thay đổi trực tiếp dạng nét viền của hình này có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Xác định xem việc thay đổi mũi tên có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Xác định xem việc thay đổi mũi tên có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Xác định xem việc thay đổi loại hình có bị cấm hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Xác định xem việc thay đổi loại hình có bị cấm hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |