---
title: IEffectFormat
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Şeklin efekt özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ieffectformat/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Shape’in efekt özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Tüm efektler devre dışı bırakılmışsa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi gibi) true döndürür. |
| [getBlurEffect()](#getBlurEffect--) | Bulanık efekt. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Bulanık efekt. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Dolgu kaplama efekti. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Dolgu kaplama efekti. |
| [getGlowEffect()](#getGlowEffect--) | Parıltı efekti. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Parıltı efekti. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | İç gölge. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | İç gölge. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Dış gölge. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Dış gölge. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Önceden tanımlı gölge. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Önceden tanımlı gölge. |
| [getReflectionEffect()](#getReflectionEffect--) | Yansıma. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Yansıma. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Yumuşak kenar. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Yumuşak kenar. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Bulanık efekti ayarlar. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Dolgu kaplama efektini etkinleştirir. |
| [enableGlowEffect()](#enableGlowEffect--) | Parıltı efektini etkinleştirir. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | İç gölge efektini etkinleştirir. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Dış gölge efektini etkinleştirir. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Önceden tanımlı gölgeler efektini etkinleştirir. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Yansıma efektini etkinleştirir. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Yumuşak kenar efektini etkinleştirir. |
| [disableBlurEffect()](#disableBlurEffect--) | Bulanık efekti devre dışı bırakır. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Dolgu kaplama efektini devre dışı bırakır. |
| [disableGlowEffect()](#disableGlowEffect--) | Parıltı efektini devre dışı bırakır. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | İç gölge efektini devre dışı bırakır. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Dış gölge efektini devre dışı bırakır. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Önceden tanımlı gölge efektini devre dışı bırakır. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Yansıma efektini devre dışı bırakır. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Yumuşak kenar efektini devre dışı bırakır. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili efekt biçimlendirme verilerini alır. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Tüm efektler devre dışı bırakılmışsa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi gibi) true döndürür. Yalnızca okuma Boolean.

**Returns:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Bulanık efekt. Okuma/yazma [IBlur](../../com.aspose.slides/iblur).

**Returns:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Bulanık efekt. Okuma/yazma [IBlur](../../com.aspose.slides/iblur).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Dolgu kaplama efekti. Okuma/yazma [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Dolgu kaplama efekti. Okuma/yazma [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Parıltı efekti. Okuma/yazma [IGlow](../../com.aspose.slides/iglow).

**Returns:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Parıltı efekti. Okuma/yazma [IGlow](../../com.aspose.slides/iglow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


İç gölge. Okuma/yazma [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Returns:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


İç gölge. Okuma/yazma [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Dış gölge. Okuma/yazma [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Returns:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Dış gölge. Okuma/yazma [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Önceden tanımlı gölge. Okuma/yazma [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Returns:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Önceden tanımlı gölge. Okuma/yazma [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Yansıma. Okuma/yazma [IReflection](../../com.aspose.slides/ireflection).

**Returns:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Yansıma. Okuma/yazma [IReflection](../../com.aspose.slides/ireflection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Yumuşak kenar. Okuma/yazma [ISoftEdge](../../com.aspose.slides/isoftedge).

**Returns:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Yumuşak kenar. Okuma/yazma [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Bulanık efekti ayarlar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Dolgu kaplama efektini etkinleştirir.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Parıltı efektini etkinleştirir.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


İç gölge efektini etkinleştirir.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Dış gölge efektini etkinleştirir.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Önceden tanımlı gölgeler efektini etkinleştirir.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Yansıma efektini etkinleştirir.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Yumuşak kenar efektini etkinleştirir.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Bulanık efekti devre dışı bırakır.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Dolgu kaplama efektini devre dışı bırakır.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Parıltı efektini devre dışı bırakır.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


İç gölge efektini devre dışı bırakır.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Dış gölge efektini devre dışı bırakır.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Önceden tanımlı gölge efektini devre dışı bırakır.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Yansıma efektini devre dışı bırakır.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Yumuşak kenar efektini devre dışı bırakır.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Uygulanan kalıtımla birlikte etkili efekt biçimlendirme verilerini alır.

**Returns:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Bir [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).