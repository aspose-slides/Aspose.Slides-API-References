---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /vi/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Xác định một mặt phẳng trong đó các hiệu ứng, chẳng hạn như phát sáng và bóng đổ, được áp dụng liên quan đến hình dạng mà chúng được áp dụng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Trả về hoặc đặt một vector pháp tuyến. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Trả về hoặc đặt một vector pháp tuyến. |
| [getAnchorPoint()](#getAnchorPoint--) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Trả về hoặc đặt một điểm trong không gian 3D. |
| [getUpVector()](#getUpVector--) | Trả về hoặc đặt một vector đại diện cho hướng lên. |
| [setUpVector(float[] value)](#setUpVector-float---) | Trả về hoặc đặt một vector đại diện cho hướng lên. |

### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Trả về hoặc đặt một vector pháp tuyến. Để chính xác hơn, thuộc tính này định nghĩa một vector pháp tuyến đối với mặt của mặt phẳng backdrop. Vector được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Trả về hoặc đặt một vector pháp tuyến. Để chính xác hơn, thuộc tính này định nghĩa một vector pháp tuyến đối với mặt của mặt phẳng backdrop. Vector được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà neo mặt phẳng backdrop. Điểm 3D được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà neo mặt phẳng backdrop. Điểm 3D được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này định nghĩa một vector đại diện cho hướng lên liên quan đến mặt của mặt phẳng backdrop. Vector được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này định nghĩa một vector đại diện cho hướng lên liên quan đến mặt của mặt phẳng backdrop. Vector được biểu diễn bằng mảng 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |