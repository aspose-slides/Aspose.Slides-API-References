---
title: IRotation3D
second_title: Aspose.Slides cho Android qua Java API Reference
description: Biểu diễn phép quay 3D của biểu đồ.
type: docs
url: /vi/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Biểu diễn phép quay 3D của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRotationX()](#getRotationX--) | Trả về hoặc đặt góc quay quanh trục X, tức là |
| [setRotationX(byte value)](#setRotationX-byte-) | Trả về hoặc đặt góc quay quanh trục X, tức là |
| [getRotationY()](#getRotationY--) | Trả về hoặc đặt góc quay quanh trục Y, tức là |
| [setRotationY(int value)](#setRotationY-int-) | Trả về hoặc đặt góc quay quanh trục Y, tức là |
| [getPerspective()](#getPerspective--) | Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giữa 0 và 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giữa 0 và 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Xác định xem các trục biểu đồ có vuông góc nhau hay không, thay vì được vẽ dưới dạng phối cảnh. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Xác định xem các trục biểu đồ có vuông góc nhau hay không, thay vì được vẽ dưới dạng phối cảnh. |
| [getDepthPercents()](#getDepthPercents--) | Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 20 và 2000 phần trăm). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 20 và 2000 phần trăm). |
| [getHeightPercents()](#getHeightPercents--) | Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 5 và 500 phần trăm). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 5 và 500 phần trăm). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Trả về hoặc đặt góc quay quanh trục X, tức là theo hướng Y cho biểu đồ 3D (giữa -90 và 90 độ). Thuộc tính này tương ứng với mục 21.2.2.157 rotX (X Rotation) trong ECMA-376 và tùy chọn "Y Rotation" trong PowerPoint 2007+. Đọc/ghi byte.

**Trả về:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Trả về hoặc đặt góc quay quanh trục X, tức là theo hướng Y cho biểu đồ 3D (giữa -90 và 90 độ). Thuộc tính này tương ứng với mục 21.2.2.157 rotX (X Rotation) trong ECMA-376 và tùy chọn "Y Rotation" trong PowerPoint 2007+. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Trả về hoặc đặt góc quay quanh trục Y, tức là theo hướng X cho biểu đồ 3D (giữa 0 và 360 độ). Thuộc tính này tương ứng với mục 21.2.2.158 rotY (Y Rotation) trong ECMA-376 và tùy chọn "X Rotation" trong PowerPoint 2007+. Đọc/ghi int.

**Trả về:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Trả về hoặc đặt góc quay quanh trục Y, tức là theo hướng X cho biểu đồ 3D (giữa 0 và 360 độ). Thuộc tính này tương ứng với mục 21.2.2.158 rotY (Y Rotation) trong ECMA-376 và tùy chọn "X Rotation" trong PowerPoint 2007+. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giữa 0 và 100). Bị bỏ qua nếu thuộc tính RightAngleAxes có giá trị true. Đọc/ghi byte.

**Trả về:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giữa 0 và 100). Bị bỏ qua nếu thuộc tính RightAngleAxes có giá trị true. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Xác định xem các trục biểu đồ có vuông góc nhau hay không, thay vì được vẽ dưới dạng phối cảnh. Nói cách khác, xác định xem các góc trục biểu đồ có độc lập với góc quay hoặc độ cao của biểu đồ hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Xác định xem các trục biểu đồ có vuông góc nhau hay không, thay vì được vẽ dưới dạng phối cảnh. Nói cách khác, xác định xem các góc trục biểu đồ có độc lập với góc quay hoặc độ cao của biểu đồ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 20 và 2000 phần trăm). Đọc/ghi int.

**Trả về:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 20 và 2000 phần trăm). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 5 và 500 phần trăm). Đọc/ghi int.

**Trả về:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 5 và 500 phần trăm). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |