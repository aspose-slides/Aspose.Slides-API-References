---
title: EffectFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các thuộc tính hiệu ứng của hình dạng.
type: docs
url: /vi/com.aspose.slides/effectformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

Biểu diễn các thuộc tính hiệu ứng của hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | Trả về true nếu tất cả các hiệu ứng bị tắt (như khi mới tạo, đối tượng EffectFormat mặc định). |
| [getBlurEffect()](#getBlurEffect--) | Hiệu ứng mờ. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Hiệu ứng mờ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Hiệu ứng phủ màu. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Hiệu ứng phủ màu. |
| [getGlowEffect()](#getGlowEffect--) | Hiệu ứng phát sáng. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Hiệu ứng phát sáng. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Bóng tối bên trong. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Bóng tối bên trong. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Bóng tối bên ngoài. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Bóng tối bên ngoài. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Bóng tối cài sẵn. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Bóng tối cài sẵn. |
| [getReflectionEffect()](#getReflectionEffect--) | Phản chiếu. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Phản chiếu. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Viền mềm. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Viền mềm. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Đặt hiệu ứng mờ. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Bật hiệu ứng phủ màu. |
| [enableGlowEffect()](#enableGlowEffect--) | Bật hiệu ứng phát sáng. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Bật hiệu ứng bóng tối bên trong. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Bật hiệu ứng bóng tối bên ngoài. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Bật hiệu ứng bóng đổ cài sẵn. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Bật hiệu ứng phản chiếu. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Bật hiệu ứng viền mềm. |
| [disableBlurEffect()](#disableBlurEffect--) | Tắt hiệu ứng mờ. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Tắt hiệu ứng phủ màu. |
| [disableGlowEffect()](#disableGlowEffect--) | Tắt hiệu ứng phát sáng. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Tắt hiệu ứng bóng tối bên trong. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Tắt hiệu ứng bóng tối bên ngoài. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Tắt hiệu ứng bóng đổ cài sẵn. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Tắt hiệu ứng phản chiếu. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Tắt hiệu ứng viền mềm. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng hiệu ứng có hiệu lực với kế thừa đã áp dụng. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Kiểu long chỉ đọc.

**Trả về:**
long

### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

Trả về true nếu tất cả các hiệu ứng bị tắt (như khi mới tạo, đối tượng EffectFormat mặc định). Kiểu boolean chỉ đọc.

**Trả về:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

Hiệu ứng mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

**Trả về:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

Hiệu ứng mờ. Đọc/ghi [IBlur](../../com.aspose.slides/iblur).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

Hiệu ứng phủ màu. Đọc/ghi [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

Hiệu ứng phủ màu. Đọc/ghi [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

Hiệu ứng phát sáng. Đọc/ghi [IGlow](../../com.aspose.slides/iglow).

**Trả về:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

Hiệu ứng phát sáng. Đọc/ghi [IGlow](../../com.aspose.slides/iglow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

Bóng tối bên trong. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Trả về:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

Bóng tối bên trong. Đọc/ghi [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

Bóng tối bên ngoài. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Trả về:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

Bóng tối bên ngoài. Đọc/ghi [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

Bóng tối cài sẵn. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Trả về:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

Bóng tối cài sẵn. Đọc/ghi [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

Phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Trả về:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

Phản chiếu. Đọc/ghi [IReflection](../../com.aspose.slides/ireflection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

Viền mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Trả về:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

Viền mềm. Đọc/ghi [ISoftEdge](../../com.aspose.slides/isoftedge).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

Thiết lập hiệu ứng mờ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Bán kính. |
| grow | boolean | Tăng. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

Bật hiệu ứng phủ màu.

### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

Bật hiệu ứng phát sáng.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

Bật hiệu ứng bóng tối bên trong.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

Bật hiệu ứng bóng tối bên ngoài.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

Bật hiệu ứng bóng đổ cài sẵn.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

Bật hiệu ứng phản chiếu.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

Bật hiệu ứng viền mềm.

### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

Tắt hiệu ứng mờ.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

Tắt hiệu ứng phủ màu.

### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

Tắt hiệu ứng phát sáng.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

Tắt hiệu ứng bóng tối bên trong.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

Tắt hiệu ứng bóng tối bên ngoài.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

Tắt hiệu ứng bóng đổ cài sẵn.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

Tắt hiệu ứng phản chiếu.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

Tắt hiệu ứng viền mềm.

### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng hiệu ứng có hiệu lực với kế thừa đã áp dụng.

--------------------

> ``` 
> Ví dụ này minh họa cách lấy một số thuộc tính hiệu ứng thực tế của hình dạng.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
> 	else
>  	{
>  		if (effectiveEffectFormat.getBlurEffect() != null)
>  			System.out.println("Blur effect radius: " + effectiveEffectFormat.getBlurEffect().getRadius());
>  		if (effectiveEffectFormat.getFillOverlayEffect() != null)
>  			System.out.println("Fill overlay effect fill type: " + effectiveEffectFormat.getFillOverlayEffect().getFillFormat().getFillType());
>  		if (effectiveEffectFormat.getGlowEffect() != null)
>  			System.out.println("Glow effect color: " + effectiveEffectFormat.getGlowEffect().getColor());
>  		if (effectiveEffectFormat.getInnerShadowEffect() != null)
>  			System.out.println("Inner shadow effect shadow color: " + effectiveEffectFormat.getInnerShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getOuterShadowEffect() != null)
>  			System.out.println("Outer shadow effect shadow color: " + effectiveEffectFormat.getOuterShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getPresetShadowEffect() != null)
>  			System.out.println("Preset shadow effect shadow color: " + effectiveEffectFormat.getPresetShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getReflectionEffect() != null)
>  			System.out.println("Reflection effect distance: " + effectiveEffectFormat.getReflectionEffect().getDistance());
>  		if (effectiveEffectFormat.getSoftEdgeEffect() != null)
>  			System.out.println("Soft edge effect radius: " + effectiveEffectFormat.getSoftEdgeEffect().getRadius());
>  	}
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).