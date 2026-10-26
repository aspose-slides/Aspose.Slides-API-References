---
title: IThreeDFormat
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho các thuộc tính 3D.
type: docs
url: /vi/com.aspose.slides/ithreedformat/
---
**Tất cả các Interface được triển khai:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Đại diện cho các thuộc tính 3D.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Trả về hoặc đặt độ rộng của một đường viền 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Trả về hoặc đặt độ rộng của một đường viền 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Trả về hoặc đặt độ cao của một hiệu ứng đùn. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Trả về hoặc đặt độ cao của một hiệu ứng đùn. |
| [getDepth()](#getDepth--) | Trả về hoặc đặt độ sâu của một hình dạng 3D. |
| [setDepth(double value)](#setDepth-double-) | Trả về hoặc đặt độ sâu của một hình dạng 3D. |
| [getBevelTop()](#getBevelTop--) | Trả về hoặc đặt loại của một góc cạnh trên 3D. |
| [getBevelBottom()](#getBevelBottom--) | Trả về hoặc đặt loại của một góc cạnh dưới 3D. |
| [getContourColor()](#getContourColor--) | Trả về hoặc đặt màu của một đường viền. |
| [getExtrusionColor()](#getExtrusionColor--) | Trả về hoặc đặt màu của một đùn. |
| [getCamera()](#getCamera--) | Trả về hoặc đặt cài đặt của một máy ảnh. |
| [getLightRig()](#getLightRig--) | Trả về hoặc đặt loại của một nguồn sáng. |
| [getMaterial()](#getMaterial--) | Trả về hoặc đặt loại của một vật liệu. |
| [setMaterial(int value)](#setMaterial-int-) | Trả về hoặc đặt loại của một vật liệu. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng 3D hiệu quả với tính kế thừa đã áp dụng. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Trả về hoặc đặt độ rộng của một đường viền 3D. Đọc/ghi double.

**Trả về:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Trả về hoặc đặt độ rộng của một đường viền 3D. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Trả về hoặc đặt độ cao của một hiệu ứng đùn. Đọc/ghi double.

**Trả về:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Trả về hoặc đặt độ cao của một hiệu ứng đùn. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Trả về hoặc đặt độ sâu của một hình dạng 3D. Đọc/ ghi double.

**Trả về:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Trả về hoặc đặt độ sâu của một hình dạng 3D. Đọc/ ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Trả về hoặc đặt loại của một góc cạnh trên 3D. Chỉ đọc [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Trả về:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Trả về hoặc đặt loại của một góc cạnh dưới 3D. Chỉ đọc [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Trả về:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Trả về hoặc đặt màu của một đường viền. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Trả về hoặc đặt màu của một đùn. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Trả về hoặc đặt cài đặt của một máy ảnh. Chỉ đọc [ICamera](../../com.aspose.slides/icamera).

**Trả về:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Trả về hoặc đặt loại của một nguồn sáng. Chỉ đọc [ILightRig](../../com.aspose.slides/ilightrig).

**Trả về:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Trả về hoặc đặt loại của một vật liệu. Đọc/ ghi [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Trả về:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Trả về hoặc đặt loại của một vật liệu. Đọc/ ghi [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng 3D hiệu quả với tính kế thừa đã áp dụng.

**Trả về:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).