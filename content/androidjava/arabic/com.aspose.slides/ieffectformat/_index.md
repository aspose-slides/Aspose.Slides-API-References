---
title: IEffectFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خصائص التأثير للشكل.
type: docs
url: /ar/com.aspose.slides/ieffectformat/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

يمثل خصائص التأثير للشكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | يرجع true إذا تم تعطيل جميع التأثيرات (كما تم إنشاؤه للتو، كائن EffectFormat الافتراضي). |
| [getBlurEffect()](#getBlurEffect--) | تأثير الضبابية. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | تأثير الضبابية. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | تأثير تغطية الملء. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | تأثير تغطية الملء. |
| [getGlowEffect()](#getGlowEffect--) | تأثير الوميض. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | تأثير الوميض. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | ظل داخلي. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | ظل داخلي. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | ظل خارجي. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | ظل خارجي. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | ظل مبدئي. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | ظل مبدئي. |
| [getReflectionEffect()](#getReflectionEffect--) | انعكاس. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | انعكاس. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | حافة ناعمة. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | حافة ناعمة. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | يضبط تأثير الضبابية. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | يفعّل تأثير تغطية الملء. |
| [enableGlowEffect()](#enableGlowEffect--) | يفعّل تأثير الوميض. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | يفعّل تأثير الظل الداخلي. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | يفعّل تأثير الظل الخارجي. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | يفعّل تأثير الظلال المبدئية. |
| [enableReflectionEffect()](#enableReflectionEffect--) | يفعّل تأثير الانعكاس. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | يفعّل تأثير الحافة الناعمة. |
| [disableBlurEffect()](#disableBlurEffect--) | يعطل تأثير الضبابية. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | يعطل تأثير تغطية الملء. |
| [disableGlowEffect()](#disableGlowEffect--) | يعطل تأثير الوميض. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | يعطل تأثير الظل الداخلي. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | يعطل تأثير الظل الخارجي. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | يعطل تأثير الظل المبدئي. |
| [disableReflectionEffect()](#disableReflectionEffect--) | يعطل تأثير الانعكاس. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | يعطل تأثير الحافة الناعمة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق التأثير الفعّال مع تطبيق الوراثة. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


يرجع true إذا تم تعطيل جميع التأثيرات (كما تم إنشاؤه للتو، كائن EffectFormat الافتراضي). قراءة فقط boolean.

**الإرجاع:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


تأثير الضبابية. قراءة/كتابة [IBlur](../../com.aspose.slides/iblur).

**الإرجاع:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


تأثير الضبابية. قراءة/كتابة [IBlur](../../com.aspose.slides/iblur).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


تأثير تغطية الملء. قراءة/كتابة [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**الإرجاع:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


تأثير تغطية الملء. قراءة/كتابة [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


تأثير الوميض. قراءة/كتابة [IGlow](../../com.aspose.slides/iglow).

**الإرجاع:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


تأثير الوميض. قراءة/كتابة [IGlow](../../com.aspose.slides/iglow).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


ظل داخلي. قراءة/كتابة [IInnerShadow](../../com.aspose.slides/iinnershadow).

**الإرجاع:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


ظل داخلي. قراءة/كتابة [IInnerShadow](../../com.aspose.slides/iinnershadow).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


ظل خارجي. قراءة/كتابة [IOuterShadow](../../com.aspose.slides/ioutershadow).

**الإرجاع:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


ظل خارجي. قراءة/كتابة [IOuterShadow](../../com.aspose.slides/ioutershadow).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


ظل مبدئي. قراءة/كتابة [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**الإرجاع:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


ظل مبدئي. قراءة/كتابة [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


انعكاس. قراءة/كتابة [IReflection](../../com.aspose.slides/ireflection).

**الإرجاع:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


انعكاس. قراءة/كتابة [IReflection](../../com.aspose.slides/ireflection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


حافة ناعمة. قراءة/كتابة [ISoftEdge](../../com.aspose.slides/isoftedge).

**الإرجاع:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


حافة ناعمة. قراءة/كتابة [ISoftEdge](../../com.aspose.slides/isoftedge).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


يضبط تأثير الضبابية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| radius | double | نصف القطر. |
| grow | boolean | نمو. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


يفعّل تأثير تغطية الملء.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


يفعّل تأثير الوميض.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


يفعّل تأثير الظل الداخلي.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


يفعّل تأثير الظل الخارجي.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


يفعّل تأثير الظلال المبدئية.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


يفعّل تأثير الانعكاس.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


يفعّل تأثير الحافة الناعمة.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


يعطل تأثير الضبابية.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


يعطل تأثير تغطية الملء.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


يعطل تأثير الوميض.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


يعطل تأثير الظل الداخلي.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


يعطل تأثير الظل الخارجي.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


يعطل تأثير الظل المبدئي.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


يعطل تأثير الانعكاس.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


يعطل تأثير الحافة الناعمة.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


يحصل على بيانات تنسيق التأثير الفعّال مع تطبيق الوراثة.

**الإرجاع:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).