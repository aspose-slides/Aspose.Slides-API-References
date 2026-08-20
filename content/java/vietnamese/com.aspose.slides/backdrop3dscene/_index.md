---
title: Backdrop3DScene
second_title: Tham khảo API Aspose.Slides cho Java
description: Xác định một mặt phẳng mà các hiệu ứng như glow và shadow được áp dụng liên quan đến hình dạng mà chúng được áp dụng.
type: docs
url: /vi/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Xác định một mặt phẳng mà các hiệu ứng, chẳng hạn như glow và shadow, được áp dụng liên quan đến hình dạng mà chúng được áp dụng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Trả về hoặc đặt một vector pháp tuyến. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Trả về hoặc đặt một vector pháp tuyến. |
| [getAnchorPoint()](#getAnchorPoint--) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [getUpVector()](#getUpVector--) | Trả về hoặc đặt một vector biểu thị hướng lên. |
| [setUpVector(float[] value)](#setUpVector-float---) | Trả về hoặc đặt một vector biểu thị hướng lên. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Kiểu long chỉ đọc.

**Trả về:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Trả về hoặc đặt một vector pháp tuyến. Cụ thể hơn, thuộc tính này định nghĩa một vector pháp tuyến với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Trả về hoặc đặt một vector pháp tuyến. Cụ thể hơn, thuộc tính này định nghĩa một vector pháp tuyến với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian làm neo cho mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian làm neo cho mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Trả về hoặc đặt một vector biểu thị hướng lên. Cụ thể hơn, thuộc tính này định nghĩa một vector biểu thị hướng lên liên quan đến mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Trả về hoặc đặt một vector biểu thị hướng lên. Cụ thể hơn, thuộc tính này định nghĩa một vector biểu thị hướng lên liên quan đến mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |