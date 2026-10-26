---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /vi/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Xác định một mặt phẳng mà trong đó các hiệu ứng, chẳng hạn như phát sáng và bóng, được áp dụng liên quan tới hình dạng mà chúng được áp dụng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Trả về hoặc đặt một vector pháp. Để chính xác hơn, thuộc tính này xác định một vector vuông góc với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Trả về hoặc đặt một vector pháp. Để chính xác hơn, thuộc tính này xác định một vector vuông góc với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà neo mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Trả về hoặc đặt một điểm trong không gian 3D. Điểm này là điểm trong không gian mà neo mặt phẳng nền. Điểm 3D được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này xác định một vector đại diện cho hướng lên so với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Trả về:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Trả về hoặc đặt một vector đại diện cho hướng lên. Để chính xác hơn, thuộc tính này xác định một vector đại diện cho hướng lên so với mặt của mặt phẳng nền. Vector được biểu diễn bằng mảng gồm 3 giá trị float xác định tọa độ X, Y và Z. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |