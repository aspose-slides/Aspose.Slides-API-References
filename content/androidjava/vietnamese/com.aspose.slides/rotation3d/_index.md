---
title: Rotation3D
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn việc quay 3D của biểu đồ.
type: docs
url: /vi/com.aspose.slides/rotation3d/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Biểu diễn phép quay 3D của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRotationX()](#getRotationX--) | Trả về hoặc đặt độ quay quanh trục X, tức là |
| [setRotationX(byte value)](#setRotationX-byte-) | Trả về hoặc đặt độ quay quanh trục X, tức là |
| [getRotationY()](#getRotationY--) | Trả về hoặc đặt độ quay quanh trục Y, tức là |
| [setRotationY(int value)](#setRotationY-int-) | Trả về hoặc đặt độ quay quanh trục Y, tức là |
| [getPerspective()](#getPerspective--) | Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giá trị từ 0 đến 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giá trị từ 0 đến 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Xác định liệu các trục của biểu đồ có vuông góc hay không, thay vì được vẽ dưới dạng phối cảnh. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Xác định liệu các trục của biểu đồ có vuông góc hay không, thay vì được vẽ dưới dạng phối cảnh. |
| [getDepthPercents()](#getDepthPercents--) | Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 20 đến 2000 phần trăm). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 20 đến 2000 phần trăm). |
| [getHeightPercents()](#getHeightPercents--) | Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 5 đến 500 phần trăm). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 5 đến 500 phần trăm). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Trả về hoặc đặt độ quay quanh trục X, tức là theo hướng Y cho biểu đồ 3D (giá trị từ -90 đến 90 độ). Thuộc tính này tương ứng với mục 21.2.2.157 rotX (X Rotation) trong ECMA-376 và tùy chọn “Y Rotation” trong PowerPoint 2007+. Đọc/ghi byte.

**Trả về:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Trả về hoặc đặt độ quay quanh trục X, tức là theo hướng Y cho biểu đồ 3D (giá trị từ -90 đến 90 độ). Thuộc tính này tương ứng với mục 21.2.157 rotX (X Rotation) trong ECMA-376 và tùy chọn “Y Rotation” trong PowerPoint 2007+. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Trả về hoặc đặt độ quay quanh trục Y, tức là theo hướng X cho biểu đồ 3D (giá trị từ 0 đến 360 độ). Thuộc tính này tương ứng với mục 21.2.2.158 rotY (Y Rotation) trong ECMA-376 và tùy chọn “X Rotation” trong PowerPoint 2007+. Đọc/ghi int.

**Trả về:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Trả về hoặc đặt độ quay quanh trục Y, tức là theo hướng X cho biểu đồ 3D (giá trị từ 0 đến 360 độ). Thuộc tính này tương ứng với mục 21.2.2.158 rotY (Y Rotation) trong ECMA-376 và tùy chọn “X Rotation” trong PowerPoint 2007+. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giá trị từ 0 đến 240). Bỏ qua nếu giá trị thuộc tính RightAngleAxes là true. Đọc/ghi byte.

**Trả về:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giá trị từ 0 đến 240). Bỏ qua nếu giá trị thuộc tính RightAngleAxes là true. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Xác định liệu các trục của biểu đồ có vuông góc hay không, thay vì được vẽ dưới dạng phối cảnh. Nói cách khác, nó xác định liệu các góc của trục biểu đồ có độc lập với việc quay hoặc nâng của biểu đồ hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Xác định liệu các trục của biểu đồ có vuông góc hay không, thay vì được vẽ dưới dạng phối cảnh. Nói cách khác, nó xác định liệu các góc của trục biểu đồ có độc lập với việc quay hoặc nâng của biểu đồ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 20 đến 2000 phần trăm). Đọc/ghi int.

**Trả về:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 20 đến 2000 phần trăm). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 5 đến 500 phần trăm). Đọc/ghi int.

**Trả về:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Xác định chiều cao của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giá trị từ 5 đến 500 phần trăm). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject