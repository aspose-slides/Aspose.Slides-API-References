---
title: IMotionEffect
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn hành vi của hiệu ứng chuyển động.
type: docs
url: /vi/com.aspose.slides/imotioneffect/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Đại diện cho hành vi của hiệu ứng chuyển động của hiệu ứng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrom()](#getFrom--) | Xác định tọa độ x/y để bắt đầu hoạt ảnh (tính bằng phần trăm). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Xác định tọa độ x/y để bắt đầu hoạt ảnh (tính bằng phần trăm). |
| [getTo()](#getTo--) | Xác định vị trí mục tiêu cho hiệu ứng chuyển động của hoạt ảnh (tính bằng phần trăm). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Xác định vị trí mục tiêu cho hiệu ứng chuyển động của hoạt ảnh (tính bằng phần trăm). |
| [getBy()](#getBy--) | Mô tả giá trị độ dịch tương đối cho hoạt ảnh (tính bằng phần trăm). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Mô tả giá trị độ dịch tương đối cho hoạt ảnh (tính bằng phần trăm). |
| [getRotationCenter()](#getRotationCenter--) | Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. |
| [getOrigin()](#getOrigin--) | Xác định nguồn gốc của đường chuyển động tương đối với ví dụ như bố cục của slide, hoặc phần tử cha. |
| [setOrigin(int value)](#setOrigin-int-) | Xác định nguồn gốc của đường chuyển động tương đối với ví dụ như bố cục của slide, hoặc phần tử cha. |
| [getPath()](#getPath--) | Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. |
| [getPathEditMode()](#getPathEditMode--) | Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. |
| [getAngle()](#getAngle--) | Mô tả góc tương đối của đường chuyển động. |
| [setAngle(float value)](#setAngle-float-) | Mô tả góc tương đối của đường chuyển động. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Xác định tọa độ x/y để bắt đầu hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Xác định tọa độ x/y để bắt đầu hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Xác định vị trí mục tiêu cho hiệu ứng chuyển động của hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Xác định vị trí mục tiêu cho hiệu ứng chuyển động của hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Mô tả giá trị độ dịch tương đối cho hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Mô tả giá trị độ dịch tương đối cho hoạt ảnh (tính bằng phần trăm). Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Xác định nguồn gốc của đường chuyển động tương đối với ví dụ như bố cục của slide, hoặc phần tử cha. Đọc/ghi [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Trả về:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Xác định nguồn gốc của đường chuyển động tương đối với ví dụ như bố cục của slide, hoặc phần tử cha. Đọc/ghi [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. Đọc/ghi [IMotionPath](../../com.aspose.slides/imotionpath).

**Trả về:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. Đọc/ghi [IMotionPath](../../com.aspose.slides/imotionpath).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. Đọc/ghi [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Trả về:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. Đọc/ghi [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Mô tả góc tương đối của đường chuyển động. Đọc/ghi float.

**Trả về:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Mô tả góc tương đối của đường chuyển động. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |