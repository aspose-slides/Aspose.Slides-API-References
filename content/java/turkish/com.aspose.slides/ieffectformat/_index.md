---
title: IEffectFormat
second_title: Aspose.Slides için Java API Referansı
description: Şeklin efekt özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ieffectformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Şeklin efekt özelliklerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Tüm efektler devre dışı bırakılmışsa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi) true döndürür. |
| [getBlurEffect()](#getBlurEffect--) | Bulanık efekt. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Bulanık efekt. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Dolgu bindirme efekt. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Dolgu bindirme efekt. |
| [getGlowEffect()](#getGlowEffect--) | Parıltı efekt. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Parıltı efekt. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | İç gölge. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | İç gölge. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Dış gölge. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Dış gölge. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Ön ayarlı gölge. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Ön ayarlı gölge. |
| [getReflectionEffect()](#getReflectionEffect--) | Refleksiyon. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Refleksiyon. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Yumuşak kenar. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Yumuşak kenar. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Bulanık efekti ayarlar. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Dolgu bindirme efektini etkinleştirir. |
| [enableGlowEffect()](#enableGlowEffect--) | Parıltı efektini etkinleştirir. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | İç gölge efektini etkinleştirir. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Dış gölge efektini etkinleştirir. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Ön ayarlı gölgeleri etkinleştirir. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Refleksiyon efektini etkinleştirir. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Yumuşak kenar efektini etkinleştirir. |
| [disableBlurEffect()](#disableBlurEffect--) | Bulanık efekti devre dışı bırakır. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Dolgu bindirme efektini devre dışı bırakır. |
| [disableGlowEffect()](#disableGlowEffect--) | Parıltı efektini devre dışı bırakır. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | İç gölge efektini devre dışı bırakır. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Dış gölge efektini devre dışı bırakır. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Ön ayarlı gölge efektini devre dışı bırakır. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Refleksiyon efektini devre dışı bırakır. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Yumuşak kenar efektini devre dışı bırakır. |
| [getEffective()](#getEffective--) | Miras uygulanarak etkili efekt biçimlendirme verilerini alır. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Tüm efektler devre dışı bırakılmışsa (yeni oluşturulmuş, varsayılan EffectFormat nesnesi) true döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Bulanık efekt. Okunur/yazılabilir [IBlur](../../com.aspose.slides/iblur).

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Bulanık efekt. Okunur/yazılabilir [IBlur](../../com.aspose.slides/iblur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Dolgu bindirme efekt. Okunur/yazılabilir [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Dolgu bindirme efekt. Okunur/yazılabilir [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Parıltı efekt. Okunur/yazılabilir [IGlow](../../com.aspose.slides/iglow).

**Döndürür:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Parıltı efekt. Okunur/yazılabilir [IGlow](../../com.aspose.slides/iglow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

İç gölge. Okunur/yazılabilir [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Döndürür:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

İç gölge. Okunur/yazılabilir [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Dış gölge. Okunur/yazılabilir [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Döndürür:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Dış gölge. Okunur/yazılabilir [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Ön ayarlı gölge. Okunur/yazılabilir [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Döndürür:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Ön ayarlı gölge. Okunur/yazılabilir [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Refleksiyon. Okunur/yazılabilir [IReflection](../../com.aspose.slides/ireflection).

**Döndürür:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Refleksiyon. Okunur/yazılabilir [IReflection](../../com.aspose.slides/ireflection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Yumuşak kenar. Okunur/yazılabilir [ISoftEdge](../../com.aspose.slides/isoftedge).

**Döndürür:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Yumuşak kenar. Okunur/yazılabilir [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Bulanık efekti ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Dolgu bindirme efektini etkinleştirir.
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

Ön ayarlı gölgeleri etkinleştirir.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Refleksiyon efektini etkinleştirir.
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

Dolgu bindirme efektini devre dışı bırakır.
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

Ön ayarlı gölge efektini devre dışı bırakır.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Refleksiyon efektini devre dışı bırakır.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Yumuşak kenar efektini devre dışı bırakır.
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Miras uygulanarak etkili efekt biçimlendirme verilerini alır.

**Döndürür:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).