---
title: IEffectFormatEffectiveData
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đối tượng bất biến chứa các thuộc tính định dạng hiệu ứng hiệu lực.
type: docs
url: /vi/com.aspose.slides/ieffectformateffectivedata/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

Đối tượng bất biến chứa các thuộc tính định dạng hiệu ứng hiệu lực.

--------------------

Giao diện này được sử dụng cùng với giao diện [IEffectFormat](../../com.aspose.slides/ieffectformat) để trả về các giá trị định dạng hiệu lực có áp dụng kế thừa.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Trả về true nếu tất cả các hiệu ứng bị vô hiệu hóa (như khi mới tạo, đối tượng EffectFormat mặc định). |
| [getBlurEffect()](#getBlurEffect--) | Hiệu ứng làm mờ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Hiệu ứng phủ lấp đầy. |
| [getGlowEffect()](#getGlowEffect--) | Hiệu ứng phát sáng. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Bóng đổ nội. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Bóng đổ ngoại. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Bóng đổ định trước. |
| [getReflectionEffect()](#getReflectionEffect--) | Phản chiếu. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Đầu mút mềm. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Trả về true nếu tất cả các hiệu ứng bị vô hiệu hóa (như khi mới tạo, đối tượng EffectFormat mặc định). Chỉ đọc boolean.

**Trả về:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

Hiệu ứng làm mờ. Chỉ đọc [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

**Trả về:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

Hiệu ứng phủ lấp đầy. Chỉ đọc [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

**Trả về:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

Hiệu ứng phát sáng. Chỉ đọc [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

**Trả về:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

Bóng đổ nội. Chỉ đọc [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).

**Trả về:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

Bóng đổ ngoại. Chỉ đọc [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

**Trả về:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

Bóng đổ định trước. Chỉ đọc [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

**Trả về:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

Phản chiếu. Chỉ đọc [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

**Trả về:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

Đầu mút mềm. Chỉ đọc [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

**Trả về:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)