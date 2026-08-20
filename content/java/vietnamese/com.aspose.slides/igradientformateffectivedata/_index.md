---
title: IGradientFormatEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đối tượng bất biến chứa các thuộc tính tô nền gradient hiệu quả.
type: docs
url: /vi/com.aspose.slides/igradientformateffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính tô nền gradient hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) và [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Trả về chế độ lật cho một gradient. |
| [getGradientDirection()](#getGradientDirection--) | Trả về kiểu của một gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Trả về góc của một gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Xác định xem gradient có được mở rộng hay không. |
| [getGradientShape()](#getGradientShape--) | Trả về hình dạng của một gradient. |
| [getGradientStops()](#getGradientStops--) | Trả về tập hợp các điểm dừng của gradient. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Trả về chế độ lật cho một gradient. chỉ đọc [TileFlip](../../com.aspose.slides/tileflip).

**Trả về:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Trả về kiểu của một gradient. chỉ đọc [GradientDirection](../../com.aspose.slides/gradientdirection).

**Trả về:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Trả về góc của một gradient. chỉ đọc float.

**Trả về:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Xác định xem gradient có được mở rộng hay không. chỉ đọc boolean.

**Trả về:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Trả về hình dạng của một gradient. chỉ đọc [GradientShape](../../com.aspose.slides/gradientshape).

**Trả về:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Trả về tập hợp các điểm dừng của gradient. chỉ đọc [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Trả về:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)