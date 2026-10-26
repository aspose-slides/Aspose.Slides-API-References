---
title: Backdrop3DScene
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Xác định một mặt phẳng mà các hiệu ứng như phát sáng và bóng đổ được áp dụng liên quan tới hình dạng mà chúng được áp dụng.
type: docs
url: /vi/com.aspose.slides/backdrop3dscene/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Xác định một mặt phẳng mà các hiệu ứng, chẳng hạn như phát sáng và bóng đổ, được áp dụng liên quan tới hình dạng mà chúng được áp dụng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Trả về hoặc đặt một vector pháp tuyến. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Trả về hoặc đặt một vector pháp tuyến. |
| [getAnchorPoint()](#getAnchorPoint--) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [getUpVector()](#getUpVector--) | Trả về hoặc đặt một vector đại diện cho hướng lên. |
| [setUpVector(float[] value)](#setUpVector-float---) | Trả về hoặc đặt một vector đại diện cho hướng lên. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Trả về hoặc đặt một vector pháp tuyến. Để chính xác hơn, thuộc tính này định nghĩa một vector vuông góc với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Trả về hoặc đặt một vector pháp tuyến. Để chính xác hơn, thuộc tính này định nghĩa một vector vuông góc với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà làm neo cho mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà làm neo cho mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này định nghĩa một vector đại diện cho hướng lên liên quan tới mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này định nghĩa một vector đại diện cho hướng lên liên quan tới mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |