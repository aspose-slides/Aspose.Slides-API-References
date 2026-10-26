---
title: IColorEffect
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn hiệu ứng màu cho một hành vi hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/icoloreffect/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Biểu diễn hiệu ứng màu cho một hành vi hoạt ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrom()](#getFrom--) | Giá trị này được sử dụng để chỉ định màu bắt đầu của hành vi. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Giá trị này được sử dụng để chỉ định màu bắt đầu của hành vi. |
| [getTo()](#getTo--) | Mô tả màu kết quả cho sự thay đổi màu trong hoạt ảnh. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Mô tả màu kết quả cho sự thay đổi màu trong hoạt ảnh. |
| [getBy()](#getBy--) | Mô tả giá trị độ dịch tương đối cho hoạt ảnh màu. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Mô tả giá trị độ dịch tương đối cho hoạt ảnh màu. |
| [getColorSpace()](#getColorSpace--) | Biểu diễn không gian màu của hành vi. |
| [setColorSpace(int value)](#setColorSpace-int-) | Biểu diễn không gian màu của hành vi. |
| [getDirection()](#getDirection--) | Xác định hướng mà hue sẽ quay quanh bánh xe màu. |
| [setDirection(int value)](#setDirection-int-) | Xác định hướng mà hue sẽ quay quanh bánh xe màu. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Giá trị này được sử dụng để chỉ định màu bắt đầu của hành vi. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Giá trị này được sử dụng để chỉ định màu bắt đầu của hành vi. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Mô tả màu kết quả cho sự thay đổi màu trong hoạt ảnh. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Mô tả màu kết quả cho sự thay đổi màu trong hoạt ảnh. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Mô tả giá trị độ dịch tương đối cho hoạt ảnh màu. Đọc/ghi [IColorOffset](../../com.aspose.slides/icoloroffset).

**Trả về:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Mô tả giá trị độ dịch tương đối cho hoạt ảnh màu. Đọc/ghi [IColorOffset](../../com.aspose.slides/icoloroffset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Biểu diễn không gian màu của hành vi. Đọc/ghi [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Trả về:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Biểu diễn không gian màu của hành vi. Đọc/ghi [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Xác định hướng mà hue sẽ quay quanh bánh xe màu. Đọc/ghi [ColorDirection](../../com.aspose.slides/colordirection).

**Trả về:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Xác định hướng mà hue sẽ quay quanh bánh xe màu. Đọc/ghi [ColorDirection](../../com.aspose.slides/colordirection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| value | int |  |