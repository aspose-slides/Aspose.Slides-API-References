---
title: IThreeDFormatEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
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

Giao diện này được sử dụng cùng với giao diện [IThreeDFormat](../../com.aspose.slides/ithreedformat) để trả về các giá trị định dạng hiệu quả với tính kế thừa được áp dụng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Trả về chiều rộng của một đường viền 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Trả về chiều cao của một hiệu ứng extrude. |
| [getDepth()](#getDepth--) | Trả về độ sâu của một hình dạng 3D. |
| [getBevelTop()](#getBevelTop--) | Trả về loại của một bevel trên 3D. |
| [getBevelBottom()](#getBevelBottom--) | Trả về loại của một bevel dưới 3D. |
| [getContourColor()](#getContourColor--) | Trả về màu của một đường viền. |
| [getExtrusionColor()](#getExtrusionColor--) | Trả về màu của một extrude. |
| [getCamera()](#getCamera--) | Trả về cài đặt của một camera. |
| [getLightRig()](#getLightRig--) | Trả về loại của một ánh sáng. |
| [getMaterial()](#getMaterial--) | Trả về loại của một vật liệu. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Trả về chiều rộng của một đường viền 3D. Chỉ đọc double.

**Trả về:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Trả về chiều cao của một hiệu ứng extrude. Chỉ đọc double.

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


Trả về loại của một bevel trên 3D. Chỉ đọc [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Trả về:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Trả về loại của một bevel dưới 3D. Chỉ đọc [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Trả về:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


Trả về màu của một đường viền. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


Trả về màu của một extrude. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Trả về cài đặt của một camera. Chỉ đọc [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Trả về:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Trả về loại của một ánh sáng. Chỉ đọc [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Trả về:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Trả về loại của một vật liệu. Chỉ đọc [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Trả về:**
int