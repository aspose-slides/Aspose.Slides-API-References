---
title: IAutoShapeLock
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định các thao tác nào bị vô hiệu hoá trên AutoshapeEx cha.
type: docs
url: /vi/com.aspose.slides/iautoshapelock/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

Xác định các thao tác nào bị vô hiệu hoá trên AutoshapeEx cha.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Xác định xem việc thêm hình này vào một nhóm có bị cấm hay không. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Xác định xem việc thêm hình này vào một nhóm có bị cấm hay không. |
| [getSelectLocked()](#getSelectLocked--) | Xác định xem việc chọn hình này có bị cấm hay không. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Xác định xem việc chọn hình này có bị cấm hay không. |
| [getRotateLocked()](#getRotateLocked--) | Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [getPositionLocked()](#getPositionLocked--) | Xác định xem việc di chuyển hình này có bị cấm hay không. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Xác định xem việc di chuyển hình này có bị cấm hay không. |
| [getSizeLocked()](#getSizeLocked--) | Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Xác định xem việc thay đổi trực tiếp đường viền của hình này có bị cấm hay không. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Xác định xem việc thay đổi trực tiếp đường viền của hình này có bị cấm hay không. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Xác định xem việc thay đổi đầu mũi tên có bị cấm hay không. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Xác định xem việc thay đổi đầu mũi tên có bị cấm hay không. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Xác định xem việc thay đổi loại hình có bị cấm hay không. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Xác định xem việc thay đổi loại hình có bị cấm hay không. |
| [getTextLocked()](#getTextLocked--) | Xác định xem việc chỉnh sửa văn bản có bị cấm hay không. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | Xác định xem việc chỉnh sửa văn bản có bị cấm hay không. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Xác định xem việc thêm hình này vào một nhóm có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Xác định xem việc thêm hình này vào một nhóm có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Xác định xem việc chọn hình này có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Xác định xem việc chọn hình này có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Xác định xem việc thay đổi góc quay của hình này có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Xác định xem hình này có phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

Xác định xem việc di chuyển hình này có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

Xác định xem việc di chuyển hình này có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Xác định xem việc thay đổi kích thước của hình này có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Xác định xem việc thay đổi trực tiếp đường viền của hình này có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Xác định xem việc thay đổi trực tiếp đường viền của hình này có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Xác định xem việc thay đổi các giá trị điều chỉnh có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Xác định xem việc thay đổi đầu mũi tên có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Xác định xem việc thay đổi đầu mũi tên có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Xác định xem việc thay đổi loại hình có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Xác định xem việc thay đổi loại hình có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

Xác định xem việc chỉnh sửa văn bản có bị cấm hay không. Boolean đọc-ghi.

**Trả về:**
boolean

### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

Xác định xem việc chỉnh sửa văn bản có bị cấm hay không. Boolean đọc-ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |