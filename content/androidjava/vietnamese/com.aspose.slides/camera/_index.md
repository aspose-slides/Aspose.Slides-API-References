---
title: Camera
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn Camera.
type: docs
url: /vi/com.aspose.slides/camera/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Biểu diễn Camera.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kiểu Camera. |
| [setCameraType(int value)](#setCameraType-int-) | Kiểu Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Góc nhìn Camera (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Góc nhìn Camera (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Zoom Camera (giá trị dương tính theo phần trăm). |
| [setZoom(float value)](#setZoom-float-) | Zoom Camera (giá trị dương tính theo phần trăm). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kiểu Camera. Đọc/ghi [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Trả về:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Kiểu Camera. Đọc/ghi [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Góc nhìn Camera (0-180 deg, field of View). Đọc/ghi float.

**Trả về:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Góc nhìn Camera (0-180 deg, field of View). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom Camera (giá trị dương tính theo phần trăm). Đọc/ghi float.

**Trả về:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom Camera (giá trị dương tính theo phần trăm). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Một quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Nếu bất kỳ giá trị tọa độ nào là Float.NaN, toàn bộ quay sẽ không xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Một quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Phần tử đầu tiên trong mảng trả về - vĩ độ, thứ hai - kinh độ, thứ ba - vòng quay. Trả về null nếu không có quay nào được định nghĩa.

**Trả về:**
float[]