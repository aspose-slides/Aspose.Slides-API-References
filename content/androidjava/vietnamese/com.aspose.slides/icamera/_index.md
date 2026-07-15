---
title: ICamera
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho Camera.
type: docs
url: /vi/com.aspose.slides/icamera/
---```
public interface ICamera
```

Đại diện cho Camera.
## Phương thức

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Loại Camera Đọc/Ghi [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Loại Camera Đọc/Ghi [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 độ, góc nhìn) Đọc/Ghi float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 độ, góc nhìn) Đọc/Ghi float. |
| [getZoom()](#getZoom--) | Thu phóng Camera (giá trị dương theo phần trăm) Đọc/Ghi float. |
| [setZoom(float value)](#setZoom-float-) | Thu phóng Camera (giá trị dương theo phần trăm) Đọc/Ghi float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Loại Camera Đọc/Ghi [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Trả về:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Loại Camera Đọc/Ghi [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 độ, góc nhìn) Đọc/Ghi float.

**Trả về:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 độ, góc nhìn) Đọc/Ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Thu phóng Camera (giá trị dương theo phần trăm) Đọc/Ghi float.

**Trả về:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Thu phóng Camera (giá trị dương theo phần trăm) Đọc/Ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Nếu bất kỳ giá trị tọa độ nào là Float.NaN, mọi phép quay sẽ không xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| latitude | float | Giá trị vĩ độ float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, thứ hai - kinh độ, thứ ba - vòng quay. Trả về null nếu không có phép quay nào được định nghĩa.

**Trả về:**
float[] - Mảng các giá trị quay dưới dạng float[].