---
title: IGradientFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho định dạng gradient.
type: docs
url: /vi/com.aspose.slides/igradientformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Đại diện cho định dạng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Trả về hoặc thiết lập chế độ lật cho gradient. |
| [setTileFlip(int value)](#setTileFlip-int-) | Trả về hoặc thiết lập chế độ lật cho gradient. |
| [getGradientDirection()](#getGradientDirection--) | Trả về hoặc thiết lập kiểu của gradient. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Trả về hoặc thiết lập kiểu của gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Trả về hoặc thiết lập góc của gradient. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Trả về hoặc thiết lập góc của gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Xác định liệu gradient có được thu phóng hay không. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Xác định liệu gradient có được thu phóng hay không. |
| [getGradientShape()](#getGradientShape--) | Trả về hoặc thiết lập hình dạng của gradient. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Trả về hoặc thiết lập hình dạng của gradient. |
| [getGradientStops()](#getGradientStops--) | Trả về bộ sưu tập các điểm dừng gradient. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Trả về hoặc thiết lập chế độ lật cho gradient. Đọc/ghi [TileFlip](../../com.aspose.slides/tileflip).

**Trả về:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Trả về hoặc thiết lập chế độ lật cho gradient. Đọc/ghi [TileFlip](../../com.aspose.slides/tileflip).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Trả về hoặc thiết lập kiểu của gradient. Đọc/ghi [GradientDirection](../../com.aspose.slides/gradientdirection).

**Trả về:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```


Trả về hoặc thiết lập kiểu của gradient. Đọc/ghi [GradientDirection](../../com.aspose.slides/gradientdirection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Trả về hoặc thiết lập góc của gradient. Đọc/ghi float.

**Trả về:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```


Trả về hoặc thiết lập góc của gradient. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```


Xác định liệu gradient có được thu phóng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```


Xác định liệu gradient có được thu phóng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Trả về hoặc thiết lập hình dạng của gradient. Đọc/ghi [GradientShape](../../com.aspose.slides/gradientshape).

**Trả về:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```


Trả về hoặc thiết lập hình dạng của gradient. Đọc/ghi [GradientShape](../../com.aspose.slides/gradientshape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```


Trả về bộ sưu tập các điểm dừng gradient. Chỉ đọc [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Trả về:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)