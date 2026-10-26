---
title: EffectFormat
second_title: Aspose.Slides for Java API Referansı
description: Şeklin efekt özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/effectformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

Şeklin efekt özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | Tüm efektler devre dışı bırakıldıysa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi gibi) true döndürür. |
| [getBlurEffect()](#getBlurEffect--) | Bulanıklaştırma efekti. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Bulanıklaştırma efekti. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Dolgu bindirme efekti. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Dolgu bindirme efekti. |
| [getGlowEffect()](#getGlowEffect--) | Parlama efekti. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Parlama efekti. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | İç gölge. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | İç gölge. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Dış gölge. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Dış gölge. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Öntanımlı gölge. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Öntanımlı gölge. |
| [getReflectionEffect()](#getReflectionEffect--) | Yansıma. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Yansıma. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Yumuşak kenar. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Yumuşak kenar. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Bulanıklaştırma efektini ayarlar. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Dolgu bindirme efektini etkinleştirir. |
| [enableGlowEffect()](#enableGlowEffect--) | Parlama efektini etkinleştirir. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | İç gölge efektini etkinleştirir. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Dış gölge efektini etkinleştirir. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Öntanımlı gölgeler efektini etkinleştirir. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Yansıma efektini etkinleştirir. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Yumuşak kenar efektini etkinleştirir. |
| [disableBlurEffect()](#disableBlurEffect--) | Bulanıklaştırma efektini devre dışı bırakır. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Dolgu bindirme efektini devre dışı bırakır. |
| [disableGlowEffect()](#disableGlowEffect--) | Parlama efektini devre dışı bırakır. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | İç gölge efektini devre dışı bırakır. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Dış gölge efektini devre dışı bırakır. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Öntanımlı gölge efektini devre dışı bırakır. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Yansıma efektini devre dışı bırakır. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Yumuşak kenar efektini devre dışı bırakır. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili efekt biçimlendirme verilerini alır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okuma long.

**Döndürür:**
long
### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

Tüm efektler devre dışı bırakıldıysa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi gibi) true döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

Bulanıklaştırma efekti. Okuma/yazma [IBlur](../../com.aspose.slides/iblur).

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

Bulanıklaştırma efekti. Okuma/yazma [IBlur](../../com.aspose.slides/iblur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

Dolgu bindirme efekti. Okuma/yazma [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

Dolgu bindirme efekti. Okuma/yazma [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

Parlama efekti. Okuma/yazma [IGlow](../../com.aspose.slides/iglow).

**Döndürür:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

Parlama efekti. Okuma/yazma [IGlow](../../com.aspose.slides/iglow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

İç gölge. Okuma/yazma [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Döndürür:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

İç gölge. Okuma/yazma [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

Dış gölge. Okuma/yazma [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Döndürür:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

Dış gölge. Okuma/yazma [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

Öntanımlı gölge. Okuma/yazma [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Döndürür:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

Öntanımlı gölge. Okuma/yazma [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

Yansıma. Okuma/yazma [IReflection](../../com.aspose.slides/ireflection).

**Döndürür:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

Yansıma. Okuma/yazma [IReflection](../../com.aspose.slides/ireflection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

Yumuşak kenar. Okuma/yazma [ISoftEdge](../../com.aspose.slides/isoftedge).

**Döndürür:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

Yumuşak kenar. Okuma/yazma [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

Bulanıklaştırma efektini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

Dolgu bindirme efektini etkinleştirir.
### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

Parlama efektini etkinleştirir.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

İç gölge efektini etkinleştirir.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

Dış gölge efektini etkinleştirir.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

Öntanımlı gölgeler efektini etkinleştirir.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

Yansıma efektini etkinleştirir.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

Yumuşak kenar efektini etkinleştirir.
### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

Bulanıklaştırma efektini devre dışı bırakır.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

Dolgu bindirme efektini devre dışı bırakır.
### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

Parlama efektini devre dışı bırakır.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

İç gölge efektini devre dışı bırakır.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

Dış gölge efektini devre dışı bırakır.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

Öntanımlı gölge efektini devre dışı bırakır.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

Yansıma efektini devre dışı bırakır.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

Yumuşak kenar efektini devre dışı bırakır.
### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili efekt biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some of shape's effective effect properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
>  	else
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


**Döndürür:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - bir [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).