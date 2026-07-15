---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /vi/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Biểu diễn LightRig.
## Phương thức

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Hướng ánh sáng. |
| [setDirection(int value)](#setDirection-int-) | Hướng ánh sáng. |
| [getLightType()](#getLightType--) | Biểu diễn ánh sáng mẫu bên phải có thể được áp dụng cho một hình dạng. |
| [setLightType(int value)](#setLightType-int-) | Biểu diễn ánh sáng mẫu bên phải có thể được áp dụng cho một hình dạng. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Hướng ánh sáng. Đọc/ghi [LightingDirection](../../com.aspose.slides/lightingdirection).

**Trả về:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Hướng ánh sáng. Đọc/ghi [LightingDirection](../../com.aspose.slides/lightingdirection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Biểu diễn ánh sáng mẫu bên phải có thể được áp dụng cho một hình dạng. Light rig đại diện cho một nhóm ánh sáng được định hướng theo cách cụ thể so với cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Trả về:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Biểu diễn ánh sáng mẫu bên phải có thể được áp dụng cho một hình dạng. Light rig đại diện cho một nhóm ánh sáng được định hướng theo cách cụ thể so với cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| latitude | float | Tọa độ vĩ độ dạng float |
| longitude | float | Tọa độ kinh độ dạng float |
| revolution | float | Tọa độ vòng quay dạng float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, phần tử thứ hai - kinh độ, phần tử thứ ba - vòng quay.

**Trả về:**
float[] - Tọa độ quay dưới dạng float[]