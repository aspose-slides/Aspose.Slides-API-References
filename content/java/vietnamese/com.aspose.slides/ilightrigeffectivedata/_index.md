---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
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

| Phương thức | Mô tả |
| --- | --- |
| [getDirection()](#getDirection--) | Hướng ánh sáng. |
| [getLightType()](#getLightType--) | Đại diện cho một ánh sáng preset có thể áp dụng cho một hình dạng. |
| [getRotation()](#getRotation--) | Một phép quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. |

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

Đại diện cho một ánh sáng preset có thể áp dụng cho một hình dạng. Bộ rig ánh sáng đại diện cho một nhóm ánh sáng được định hướng theo cách cụ thể so với cảnh 3D. Chỉ đọc [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Trả về:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Một phép quay được xác định thông qua việc sử dụng tọa độ vĩ độ, tọa độ kinh độ và một vòng quay quanh trục như các tọa độ vĩ độ và kinh độ. Phần tử đầu tiên trong mảng trả về - vĩ độ, phần thứ hai - kinh độ, phần thứ ba - vòng quay.

**Trả về:**
float[] - Các tọa độ quay dưới dạng float[]