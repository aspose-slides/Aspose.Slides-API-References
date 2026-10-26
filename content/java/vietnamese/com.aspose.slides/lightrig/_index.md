---
title: LightRig
second_title: Aspose.Slides cho Java Tham chiếu API
description: Biểu diễn LightRig.
type: docs
url: /vi/com.aspose.slides/lightrig/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
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
| [getLightType()](#getLightType--) | Biểu diễn một đèn preset có thể áp dụng cho một hình dạng. |
| [setLightType(int value)](#setLightType-int-) | Biểu diễn một đèn preset có thể áp dụng cho một hình dạng. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
| [getRotation()](#getRotation--) | Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Chỉ đọc long.

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


Biểu diễn một đèn preset có thể áp dụng cho một hình dạng. Light rig đại diện cho một nhóm đèn được định hướng theo cách cụ thể so với cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Trả về:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Biểu diễn một đèn preset có thể áp dụng cho một hình dạng. Light rig đại diện cho một nhóm đèn được định hướng theo cách cụ thể so với cảnh 3D. Đọc/ghi [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Nếu bất kỳ giá trị tọa độ nào là Float.NaN, toàn bộ phép quay sẽ không xác định.

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


Một phép quay được định nghĩa thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. phần tử đầu tiên trong mảng trả về - vĩ độ, thứ hai - kinh độ, thứ ba - vòng quay. Trả về null nếu không có phép quay nào được định nghĩa.

**Trả về:**
float[]