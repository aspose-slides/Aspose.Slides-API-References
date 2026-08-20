---
title: IReflection
second_title: Tham khảo API Aspose.Slides cho Java
description: Biểu thị một hiệu ứng phản chiếu.
type: docs
url: /vi/com.aspose.slides/ireflection/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

Đại diện cho hiệu ứng phản chiếu.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Xác định vị trí bắt đầu (trên dốc gradient alpha) của giá trị alpha bắt đầu (phần trăm). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Xác định vị trí bắt đầu (trên dốc gradient alpha) của giá trị alpha bắt đầu (phần trăm). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Xác định vị trí kết thúc (trên dốc gradient alpha) của giá trị alpha kết thúc (phần trăm). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Xác định vị trí kết thúc (trên dốc gradient alpha) của giá trị alpha kết thúc (phần trăm). |
| [getFadeDirection()](#getFadeDirection--) | Xác định hướng để dịch phản chiếu. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Xác định hướng để dịch phản chiếu. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Độ mờ phản chiếu ban đầu. (phần trăm) |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Độ mờ phản chiếu ban đầu. (phần trăm) |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Độ mờ phản chiếu cuối cùng. (phần trăm) |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Độ mờ phản chiếu cuối cùng. (phần trăm) |
| [getBlurRadius()](#getBlurRadius--) | Bán kính mờ. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bán kính mờ. |
| [getDirection()](#getDirection--) | Hướng phản chiếu. |
| [setDirection(float value)](#setDirection-float-) | Hướng phản chiếu. |
| [getDistance()](#getDistance--) | Khoảng cách phản chiếu. |
| [setDistance(double value)](#setDistance-double-) | Khoảng cách phản chiếu. |
| [getRectangleAlign()](#getRectangleAlign--) | Căn chỉnh hình chữ nhật. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Căn chỉnh hình chữ nhật. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Xác định góc nghiêng ngang. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Xác định góc nghiêng ngang. |
| [getSkewVertical()](#getSkewVertical--) | Xác định góc nghiêng dọc. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Xác định góc nghiêng dọc. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Xác định liệu phản chiếu có nên quay cùng hình dạng nếu hình dạng được quay hay không. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Xác định liệu phản chiếu có nên quay cùng hình dạng nếu hình dạng được quay hay không. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Xác định hệ số co dọc ngang, co âm gây lật. (phần trăm) |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Xác định hệ số co dọc ngang, co âm gây lật. (phần trăm) |
| [getScaleVertical()](#getScaleVertical--) | Xác định hệ số co dọc dọc, co âm gây lật. (phần trăm) |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Xác định hệ số co dọc dọc, co âm gây lật. (phần trăm) |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Xác định vị trí bắt đầu (trên dốc gradient alpha) của giá trị alpha bắt đầu (phần trăm). Đọc/ghi float.

**Trả về:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

Xác định vị trí bắt đầu (trên dốc gradient alpha) của giá trị alpha bắt đầu (phần trăm). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Xác định vị trí kết thúc (trên dốc gradient alpha) của giá trị alpha kết thúc (phần trăm). Đọc/ghi float.

**Trả về:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

Xác định vị trí kết thúc (trên dốc gradient alpha) của giá trị alpha kết thúc (phần trăm). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Xác định hướng để dịch phản chiếu. (angle). Đọc/ghi float.

**Trả về:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

Xác định hướng để dịch phản chiếu. (angle). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Độ mờ phản chiếu ban đầu. (phần trăm). Đọc/ghi float.

**Trả về:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

Độ mờ phản chiếu ban đầu. (phần trăm). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Độ mờ phản chiếu cuối cùng. (phần trăm). Đọc/ghi float.

**Trả về:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

Độ mờ phản chiếu cuối cùng. (phần trăm). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bán kính mờ. Đọc/ghi double.

**Trả về:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bán kính mờ. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Hướng phản chiếu. Đọc/ghi float.

**Trả về:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Hướng phản chiếu. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Khoảng cách phản chiếu. Đọc/ghi double.

**Trả về:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Khoảng cách phản chiếu. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Căn chỉnh hình chữ nhật. Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Trả về:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Căn chỉnh hình chữ nhật. Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Xác định góc nghiêng ngang. Đọc/ghi double.

**Trả về:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Xác định góc nghiêng ngang. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Xác định góc nghiêng dọc. Đọc/ghi double.

**Trả về:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Xác định góc nghiêng dọc. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Xác định liệu phản chiếu có nên quay cùng hình dạng nếu hình dạng được quay hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Xác định liệu phản chiếu có nên quay cùng hình dạng nếu hình dạng được quay hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Xác định hệ số co dọc ngang, co âm gây lật. (phần trăm) Đọc/ghi double.

**Trả về:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Xác định hệ số co dọc ngang, co âm gây lật. (phần trăm) Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Xác định hệ số co dọc dọc, co âm gây lật. (phần trăm) Đọc/ghi double.

**Trả về:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Xác định hệ số co dọc dọc, co âm gây lật. (phần trăm) Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |