---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn Camera.
type: docs
url: /vi/com.aspose.slides/icamera/
---```
public interface ICamera
```

Biểu diễn Camera.
## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Loại Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Loại Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 độ, field of View) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 độ, field of View) Read/write float. |
| [getZoom()](#getZoom--) | Camera zoom (giá trị dương theo phần trăm) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (giá trị dương theo phần trăm) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một vòng quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một vòng quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Loại Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Loại Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 độ, field of View) Read/write float.

**Returns:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 độ, field of View) Read/write float.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera zoom (giá trị dương theo phần trăm) Read/write float.

**Returns:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera zoom (giá trị dương theo phần trăm) Read/write float.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Một vòng quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Nếu bất kỳ giá trị tọa độ nào là Float.NaN, toàn bộ vòng quay sẽ không xác định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| latitude | float | Giá trị vĩ độ kiểu float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Một vòng quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, phần tử thứ hai - kinh độ, phần tử thứ ba - vòng quay. Trả về null nếu không có vòng quay nào được xác định.

**Returns:**
float[] - Mảng các giá trị quay dưới dạng float[].