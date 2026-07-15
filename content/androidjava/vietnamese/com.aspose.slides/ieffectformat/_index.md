---
title: IEffectFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các thuộc tính hiệu ứng của hình dạng.
type: docs
url: /vi/com.aspose.slides/ieffectformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Biểu diễn các thuộc tính hiệu ứng của hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Trả về true nếu tất cả các hiệu ứng đều bị vô hiệu hoá (như khi mới tạo, đối tượng EffectFormat mặc định). |
| [getBlurEffect()](#getBlurEffect--) | Hiệu ứng làm mờ. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Hiệu ứng làm mờ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Hiệu ứng phủ màu. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Hiệu ứng phủ màu. |
| [getGlowEffect()](#getGlowEffect--) | Hiệu ứng phát sáng. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Hiệu ứng phát sáng. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Hiệu ứng bóng nội. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Hiệu ứng bóng nội. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Hiệu ứng bóng ngoại. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Hiệu ứng bóng ngoại. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Hiệu ứng bóng định sẵn. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Hiệu ứng bóng định sẵn. |
| [getReflectionEffect()](#getReflectionEffect--) | Hiệu ứng phản chiếu. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Hiệu ứng phản chiếu. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Hiệu ứng cạnh mềm. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Hiệu ứng cạnh mềm. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Đặt hiệu ứng làm mờ. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Bật hiệu ứng phủ màu. |
| [enableGlowEffect()](#enableGlowEffect--) | Bật hiệu ứng phát sáng. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Bật hiệu ứng bóng nội. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Bật hiệu ứng bóng ngoại. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Bật hiệu ứng bóng định sẵn. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Bật hiệu ứng phản chiếu. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Bật hiệu ứng cạnh mềm. |
| [disableBlurEffect()](#disableBlurEffect--) | Tắt hiệu ứng làm mờ. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Tắt hiệu ứng phủ màu. |
| [disableGlowEffect()](#disableGlowEffect--) | Tắt hiệu ứng phát sáng. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Tắt hiệu ứng bóng nội. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Tắt hiệu ứng bóng ngoại. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Tắt hiệu ứng bóng định sẵn. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Tắt hiệu ứng phản chiếu. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Tắt hiệu ứng cạnh mềm. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng hiệu ứng hiệu quả với tính kế thừa đã được áp dụng. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Trả về true nếu tất cả các hiệu ứng đều bị vô hiệu hoá (như khi mới tạo, đối tượng EffectFormat mặc định). Boolean chỉ đọc.

**Trả về:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Hiệu ứng làm mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

**Trả về:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Hiệu ứng làm mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Hiệu ứng phủ màu. Đọc/ghi [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Hiệu ứng phủ màu. Đọc/ghi [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Hiệu ứng phát sáng. Đọc/ghi [IGlow](../../com.aspose.slides/iglow).

**Trả về:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Hiệu ứng phát sáng. Đọc/ghi [IGlow](../../com.aspose.slides/iglow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Hiệu ứng bóng nội. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Trả về:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Hiệu ứng bóng nội. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Hiệu ứng bóng ngoại. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Trả về:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Hiệu ứng bóng ngoại. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Hiệu ứng bóng định sẵn. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Trả về:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Hiệu ứng bóng định sẵn. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Hiệu ứng phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Trả về:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Hiệu ứng phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Hiệu ứng cạnh mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Trả về:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Hiệu ứng cạnh mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Đặt hiệu ứng làm mờ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Bán kính. |
| grow | boolean | Tăng. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Bật hiệu ứng phủ màu.
### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Bật hiệu ứng phát sáng.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Bật hiệu ứng bóng nội.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Bật hiệu ứng bóng ngoại.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Bật hiệu ứng bóng định sẵn.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Bật hiệu ứng phản chiếu.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Bật hiệu ứng cạnh mềm.
### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Tắt hiệu ứng làm mờ.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Tắt hiệu ứng phủ màu.
### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Tắt hiệu ứng phát sáng.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Tắt hiệu ứng bóng nội.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Tắt hiệu ứng bóng ngoại.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Tắt hiệu ứng bóng định sẵn.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Tắt hiệu ứng phản chiếu.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Tắt hiệu ứng cạnh mềm.
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng hiệu ứng hiệu quả với tính kế thừa đã được áp dụng.

**Trả về:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Một [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).