---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng bất biến chứa các thuộc tính rig ánh sáng hiệu quả.
type: docs
url: /vi/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Đối tượng bất biến chứa các thuộc tính rig ánh sáng hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Phương thức

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Hướng ánh sáng. |
| [getLightType()](#getLightType--) | Biểu diễn một ánh sáng đặt sẵn có thể áp dụng cho hình dạng. |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như tọa độ vĩ độ và kinh độ. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Hướng ánh sáng. Chỉ đọc [LightingDirection](../../com.aspose.slides/lightingdirection).

**Trả về:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Biểu diễn một ánh sáng đặt sẵn có thể áp dụng cho hình dạng. Light rig biểu diễn một nhóm các ánh sáng được định hướng theo cách cụ thể so với một cảnh 3D. Chỉ đọc [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Trả về:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như tọa độ vĩ độ và kinh độ. Phần tử đầu tiên trong mảng trả về - vĩ độ, phần tử thứ hai - kinh độ, phần tử thứ ba - vòng quay.

**Trả về:**
float[] - Tọa độ quay dưới dạng float[]