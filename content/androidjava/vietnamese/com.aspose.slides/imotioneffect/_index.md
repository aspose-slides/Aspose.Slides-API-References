---
title: IMotionEffect
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn hành vi hiệu ứng chuyển động của hiệu ứng.
type: docs
url: /vi/com.aspose.slides/imotioneffect/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Biểu diễn hành vi hiệu ứng chuyển động của hiệu ứng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrom()](#getFrom--) | Xác định tọa độ x/y để bắt đầu hoạt ảnh (theo phần trăm). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Xác định tọa độ x/y để bắt đầu hoạt ảnh (theo phần trăm). |
| [getTo()](#getTo--) | Xác định vị trí mục tiêu cho một hiệu ứng chuyển động hoạt ảnh (theo phần trăm). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Xác định vị trí mục tiêu cho một hiệu ứng chuyển động hoạt ảnh (theo phần trăm). |
| [getBy()](#getBy--) | Mô tả giá trị độ lệch tương đối cho hoạt ảnh (theo phần trăm). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Mô tả giá trị độ lệch tương đối cho hoạt ảnh (theo phần trăm). |
| [getRotationCenter()](#getRotationCenter--) | Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. |
| [getOrigin()](#getOrigin--) | Xác định gốc của đường chuyển động tương đối với như bố cục của slide, hoặc phần tử cha. |
| [setOrigin(int value)](#setOrigin-int-) | Xác định gốc của đường chuyển động tương đối với như bố cục của slide, hoặc phần tử cha. |
| [getPath()](#getPath--) | Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Xác định primitive đường dẫn kèm theo tọa độ cho chuyển động hoạt ảnh. |
| [getPathEditMode()](#getPathEditMode--) | Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Xác định cách đường chuyển động di chuyển khi hình dạng được di chuyển. |
| [getAngle()](#getAngle--) | Mô tả góc tương đối của đường chuyển động. |
| [setAngle(float value)](#setAngle-float-) | Mô tả góc tương đối của đường chuyển động. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Xác định tọa độ x/y để bắt đầu hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Trả về:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Xác định tọa độ x/y để bắt đầu hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Xác định vị trí mục tiêu cho một hiệu ứng chuyển động hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Trả về:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Xác định vị trí mục tiêu cho một hiệu ứng chuyển động hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Mô tả giá trị độ lệch tương đối cho hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Trả về:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Mô tả giá trị độ lệch tương đối cho hoạt ảnh (theo phần trăm). Đọc/ghi android.graphics.PointF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. Đọc/ghi android.graphics.PointF.

**Trả về:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Mô tả trung tâm quay được sử dụng để quay một đường chuyển động theo góc X. Đọc/ghi android.graphics.PointF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Xác định gốc của đường chuyển động tương đối với như bố cục của slide, hoặc phần tử cha. Đọc/ghi [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Trả về:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Xác định gốc của đường chuyển động tương đối với như bố cục của slide, hoặc phần tử cha. Đọc/ghi [MotionOriginType](../../com.aspose.slides/motionorigintype).

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