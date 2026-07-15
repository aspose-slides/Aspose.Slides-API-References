---
title: IThreeDFormatEffectiveData
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đối tượng bất biến đại diện cho các thuộc tính định dạng 3-D hiệu quả.
type: docs
url: /vi/com.aspose.slides/ithreedformateffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Đối tượng bất biến đại diện cho các thuộc tính định dạng 3-D hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [IThreeDFormat](../../com.aspose.slides/ithreedformat) để trả về các giá trị định dạng hiệu quả với kế thừa được áp dụng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Trả về độ rộng của một đường viền 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Trả về chiều cao của một hiệu ứng đùn. |
| [getDepth()](#getDepth--) | Trả về độ sâu của một hình dạng 3D. |
| [getBevelTop()](#getBevelTop--) | Trả về kiểu của một viền trên 3D. |
| [getBevelBottom()](#getBevelBottom--) | Trả về kiểu của một viền dưới 3D. |
| [getContourColor()](#getContourColor--) | Trả về màu của một đường viền. |
| [getExtrusionColor()](#getExtrusionColor--) | Trả về màu của một phép đùn. |
| [getCamera()](#getCamera--) | Trả về cài đặt của một máy ảnh. |
| [getLightRig()](#getLightRig--) | Trả về kiểu của một ánh sáng. |
| [getMaterial()](#getMaterial--) | Trả về kiểu của một vật liệu. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Trả về độ rộng của một đường viền 3D. Chỉ đọc double.

**Trả về:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Trả về chiều cao của một hiệu ứng đùn. Chỉ đọc double.

**Trả về:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Trả về độ sâu của một hình dạng 3D. Chỉ đọc double.

**Trả về:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Trả về kiểu của một viền trên 3D. Chỉ đọc [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Trả về:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Trả về kiểu của một viền dưới 3D. Chỉ đọc [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Trả về:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Trả về màu của một đường viền. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Trả về màu của một phép đùn. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Trả về cài đặt của một máy ảnh. Chỉ đọc [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Trả về:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Trả về kiểu của một ánh sáng. Chỉ đọc [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Trả về:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Trả về kiểu của một vật liệu. Chỉ đọc [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Trả về:**
int