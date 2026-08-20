---
title: IEffectFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các thuộc tính hiệu ứng của hình dạng.
type: docs
url: /vi/com.aspose.slides/ieffectformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Biểu diễn các thuộc tính hiệu ứng của hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Trả về true nếu tất cả các hiệu ứng đều bị tắt (như khi mới tạo, đối tượng EffectFormat mặc định). |
| [getBlurEffect()](#getBlurEffect--) | Hiệu ứng mờ. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Hiệu ứng mờ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Hiệu ứng phủ màu. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Hiệu ứng phủ màu. |
| [getGlowEffect()](#getGlowEffect--) | Hiệu ứng phát sáng. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Hiệu ứng phát sáng. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Bóng đổ bên trong. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Bóng đổ bên trong. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Bóng đổ bên ngoài. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Bóng đổ bên ngoài. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Bóng đổ mẫu. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Bóng đổ mẫu. |
| [getReflectionEffect()](#getReflectionEffect--) | Phản chiếu. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Phản chiếu. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Đường viền mềm. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Đường viền mềm. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Đặt hiệu ứng mờ. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Bật hiệu ứng phủ màu. |
| [enableGlowEffect()](#enableGlowEffect--) | Bật hiệu ứng phát sáng. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Bật hiệu ứng bóng đổ bên trong. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Bật hiệu ứng bóng đổ bên ngoài. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Bật hiệu ứng bóng đổ mẫu. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Bật hiệu ứng phản chiếu. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Bật hiệu ứng đường viền mềm. |
| [disableBlurEffect()](#disableBlurEffect--) | Tắt hiệu ứng mờ. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Tắt hiệu ứng phủ màu. |
| [disableGlowEffect()](#disableGlowEffect--) | Tắt hiệu ứng phát sáng. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Tắt hiệu ứng bóng đổ bên trong. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Tắt hiệu ứng bóng đổ bên ngoài. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Tắt hiệu ứng bóng đổ mẫu. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Tắt hiệu ứng phản chiếu. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Tắt hiệu ứng đường viền mềm. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng hiệu ứng thực tế với kế thừa đã được áp dụng. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Trả về true nếu tất cả các hiệu ứng đều bị tắt (như khi mới tạo, đối tượng EffectFormat mặc định). Boolean chỉ đọc.

**Trả về:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Hiệu ứng mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

**Trả về:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Hiệu ứng mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

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

Bóng đổ bên trong. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Trả về:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Bóng đổ bên trong. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Bóng đổ bên ngoài. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Trả về:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Bóng đổ bên ngoài. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Bóng đổ mẫu. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Trả về:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Bóng đổ mẫu. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Trả về:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Đường viền mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Trả về:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Đường viền mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Đặt hiệu ứng mờ.

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

Bật hiệu ứng bóng đổ bên trong.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Bật hiệu ứng bóng đổ bên ngoài.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Bật hiệu ứng bóng đổ mẫu.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Bật hiệu ứng phản chiếu.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Bật hiệu ứng đường viền mềm.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Tắt hiệu ứng mờ.

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

Tắt hiệu ứng bóng đổ bên trong.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Tắt hiệu ứng bóng đổ bên ngoài.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Tắt hiệu ứng bóng đổ mẫu.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Tắt hiệu ứng phản chiếu.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Tắt hiệu ứng đường viền mềm.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng hiệu ứng thực tế với kế thừa đã được áp dụng.

**Trả về:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).