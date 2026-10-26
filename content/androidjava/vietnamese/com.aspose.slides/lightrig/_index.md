---
title: LightRig
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn LightRig.
type: docs
url: /vi/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Biểu diễn LightRig.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Hướng ánh sáng. |
| [setDirection(int value)](#setDirection-int-) | Hướng ánh sáng. |
| [getLightType()](#getLightType--) | Biểu diễn một ánh sáng mặc định bên phải có thể được áp dụng cho một hình dạng. |
| [setLightType(int value)](#setLightType-int-) | Biểu diễn một ánh sáng mặc định bên phải có thể được áp dụng cho một hình dạng. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục dựa trên các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục dựa trên các tọa độ vĩ độ và kinh độ. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Đọc-chỉ long.

**Trả về:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Hướng ánh sáng. Đọc/ghi [LightingDirection](../../com.aspose.slides/lightingdirection).

**Trả về:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Hướng ánh sáng. Đọc/ghi [LightingDirection](../../com.aspose.slides/lightingdirection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


Biểu diễn một ánh sáng mặc định bên phải có thể được áp dụng cho một hình dạng. Light rig biểu diễn một nhóm các nguồn sáng được định hướng theo một cách cụ thể so với một cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Trả về:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Biểu diễn một ánh sáng mặc định bên phải có thể được áp dụng cho một hình dạng. Light rig biểu diễn một nhóm các nguồn sáng được định hướng theo một cách cụ thể so với một cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục dựa trên các tọa độ vĩ độ và kinh độ. Nếu bất kỳ giá trị tọa độ nào là Float.NaN, toàn bộ phép quay sẽ không được xác định.

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


Một phép quay được định nghĩa bằng cách sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục dựa trên các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, phần tử thứ hai - kinh độ, phần tử thứ ba - vòng quay. Trả về null nếu không có phép quay nào được xác định.

**Trả về:**
float[]