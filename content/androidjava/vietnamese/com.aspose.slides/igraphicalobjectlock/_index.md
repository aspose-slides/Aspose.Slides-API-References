---
title: IGraphicalObjectLock
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Xác định các thao tác nào bị vô hiệu hóa trên GraphicalObject cha.
type: docs
url: /vi/com.aspose.slides/igraphicalobjectlock/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

Xác định các thao tác nào bị vô hiệu hoá trên GraphicalObject cha.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Xác định việc thêm hình này vào một nhóm có bị cấm hay không. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Xác định việc thêm hình này vào một nhóm có bị cấm hay không. |
| [getDrilldownLocked()](#getDrilldownLocked--) | Xác định việc chọn các hình phụ của đối tượng này có bị cấm hay không. |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | Xác định việc chọn các hình phụ của đối tượng này có bị cấm hay không. |
| [getSelectLocked()](#getSelectLocked--) | Xác định việc chọn hình này có bị cấm hay không. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Xác định việc chọn hình này có bị cấm hay không. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Xác định liệu hình phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Xác định liệu hình phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. |
| [getPositionLocked()](#getPositionLocked--) | Xác định việc di chuyển hình này có bị cấm hay không. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Xác định việc di chuyển hình này có bị cấm hay không. |
| [getSizeLocked()](#getSizeLocked--) | Xác định việc thay đổi kích thước hình này có bị cấm hay không. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Xác định việc thay đổi kích thước hình này có bị cấm hay không. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Xác định việc thêm hình này vào một nhóm có bị cấm hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Xác định việc thêm hình này vào một nhóm có bị cấm hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

Xác định việc chọn các hình phụ của đối tượng này có bị cấm hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

Xác định việc chọn các hình phụ của đối tượng này có bị cấm hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Xác định việc chọn hình này có bị cấm hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Xác định việc chọn hình này có bị cấm hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Xác định liệu hình phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Xác định liệu hình phải giữ tỷ lệ khung hình khi thay đổi kích thước hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

Xác định việc di chuyển hình này có bị cấm hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

Xác định việc di chuyển hình này có bị cấm hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Xác định việc thay đổi kích thước hình này có bị cấm hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Xác định việc thay đổi kích thước hình này có bị cấm hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |