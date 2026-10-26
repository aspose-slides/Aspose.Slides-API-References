---
title: ICameraEffectiveData
second_title: Aspose.Slides cho Android qua Java API Reference
description: Đối tượng bất biến chứa các thuộc tính máy ảnh hiệu quả.
type: docs
url: /vi/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Đối tượng bất biến chứa các thuộc tính máy ảnh hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCameraType()](#getCameraType--) | Loại máy ảnh. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 độ, trường nhìn). |
| [getZoom()](#getZoom--) | Camera zoom (giá trị dương tính phần trăm). |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Loại máy ảnh. Chỉ đọc [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Trả về:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 độ, trường nhìn). Chỉ đọc float.

**Trả về:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (giá trị dương tính phần trăm). Chỉ đọc float.

**Trả về:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, phần tử thứ hai - kinh độ, phần tử thứ ba - vòng quay. Trả về null nếu không có phép quay nào được định nghĩa.

**Trả về:**
float[] - Mảng các giá trị quay dưới dạng float[].