---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đối tượng bất biến chứa các thuộc tính đổ màu gradient hiệu quả.
type: docs
url: /vi/com.aspose.slides/igradientformateffectivedata/
---
**Tất cả các giao diện đã thực thi:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính đổ màu gradient hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) và [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Trả về chế độ lật cho một gradient. |
| [getGradientDirection()](#getGradientDirection--) | Trả về kiểu của một gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Trả về góc của một gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Xác định liệu gradient có được thu phóng hay không. |
| [getGradientShape()](#getGradientShape--) | Trả về hình dạng của một gradient. |
| [getGradientStops()](#getGradientStops--) | Trả về tập hợp các điểm dừng gradient. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Trả về chế độ lật cho một gradient. Chỉ đọc [TileFlip](../../com.aspose.slides/tileflip).

**Trả về:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Trả về kiểu của một gradient. Chỉ đọc [GradientDirection](../../com.aspose.slides/gradientdirection).

**Trả về:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Trả về góc của một gradient. Chỉ đọc float.

**Trả về:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Xác định liệu một gradient có được thu phóng hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Trả về hình dạng của một gradient. Chỉ đọc [GradientShape](../../com.aspose.slides/gradientshape).

**Trả về:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Trả về tập hợp các điểm dừng gradient. Chỉ đọc [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Trả về:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)