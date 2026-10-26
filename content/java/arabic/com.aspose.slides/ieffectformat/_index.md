---
title: IEffectFormat
second_title: مرجع Aspose.Slides للـ Java API
description: يمثل خصائص التأثير للشكل.
type: docs
url: /ar/com.aspose.slides/ieffectformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

يمثل خصائص التأثير للشكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | يرجع true إذا تم تعطيل جميع التأثيرات (as just created, default EffectFormat object). |
| [getBlurEffect()](#getBlurEffect--) | تأثير الضبابية. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | تأثير الضبابية. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | تأثير تغطية التعبئة. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | تأثير تغطية التعبئة. |
| [getGlowEffect()](#getGlowEffect--) | تأثير التوهج. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | تأثير التوهج. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | ظل داخلي. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | ظل داخلي. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | ظل خارجي. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | ظل خارجي. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | ظل مسبق الإعداد. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | ظل مسبق الإعداد. |
| [getReflectionEffect()](#getReflectionEffect--) | انعكاس. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | انعكاس. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | حافة ناعمة. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | حافة ناعمة. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | يضبط تأثير الضبابية. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | يفعل تأثير تغطية التعبئة. |
| [enableGlowEffect()](#enableGlowEffect--) | يفعل تأثير التوهج. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | يفعل تأثير الظل الداخلي. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | يفعل تأثير الظل الخارجي. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | يفعل تأثير الظلال المسبقة الإعداد. |
| [enableReflectionEffect()](#enableReflectionEffect--) | يفعل تأثير الانعكاس. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | يفعل تأثير الحافة الناعمة. |
| [disableBlurEffect()](#disableBlurEffect--) | يعطل تأثير الضبابية. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | يعطل تأثير تغطية التعبئة. |
| [disableGlowEffect()](#disableGlowEffect--) | يعطل تأثير التوهج. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | يعطل تأثير الظل الداخلي. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | يعطل تأثير الظل الخارجي. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | يعطل تأثير الظل المسبق الإعداد. |
| [disableReflectionEffect()](#disableReflectionEffect--) | يعطل تأثير الانعكاس. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | يعطل تأثير الحافة الناعمة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق التأثير الفعّال مع تطبيق الوراثة. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

يرجع true إذا تم تعطيل جميع التأثيرات (as just created, default EffectFormat object). قيمة منطقية للقراءة فقط.

**القيمة المعادة:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

تأثير الضبابية. قابل للقراءة والكتابة [IBlur](../../com.aspose.slides/iblur).

**القيمة المعادة:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

تأثير الضبابية. قابل للقراءة والكتابة [IBlur](../../com.aspose.slides/iblur).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

تأثير تغطية التعبئة. قابل للقراءة والكتابة [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**القيمة المعادة:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

تأثير تغطية التعبئة. قابل للقراءة والكتابة [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

تأثير التوهج. قابل للقراءة والكتابة [IGlow](../../com.aspose.slides/iglow).

**القيمة المعادة:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

تأثير التوهج. قابل للقراءة والكتابة [IGlow](../../com.aspose.slides/iglow).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

ظل داخلي. قابل للقراءة والكتابة [IInnerShadow](../../com.aspose.slides/iinnershadow).

**القيمة المعادة:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

ظل داخلي. قابل للقراءة والكتابة [IInnerShadow](../../com.aspose.slides/iinnershadow).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

ظل خارجي. قابل للقراءة والكتابة [IOuterShadow](../../com.aspose.slides/ioutershadow).

**القيمة المعادة:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

ظل خارجي. قابل للقراءة والكتابة [IOuterShadow](../../com.aspose.slides/ioutershadow).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

ظل مسبق الإعداد. قابل للقراءة والكتابة [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**القيمة المعادة:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

ظل مسبق الإعداد. قابل للقراءة والكتابة [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

انعكاس. قابل للقراءة والكتابة [IReflection](../../com.aspose.slides/ireflection).

**القيمة المعادة:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

انعكاس. قابل للقراءة والكتابة [IReflection](../../com.aspose.slides/ireflection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

حافة ناعمة. قابل للقراءة والكتابة [ISoftEdge](../../com.aspose.slides/isoftedge).

**القيمة المعادة:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

حافة ناعمة. قابل للقراءة والكتابة [ISoftEdge](../../com.aspose.slides/isoftedge).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

يضبط تأثير الضبابية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

يفعل تأثير تغطية التعبئة.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

يفعل تأثير التوهج.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

يفعل تأثير الظل الداخلي.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

يفعل تأثير الظل الخارجي.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

يفعل تأثير الظلال المسبقة الإعداد.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

يفعل تأثير الانعكاس.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

يفعل تأثير الحافة الناعمة.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

يعطل تأثير الضبابية.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

يعطل تأثير تغطية التعبئة.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

يعطل تأثير التوهج.

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

يعطل تأثير الظل المسبق الإعداد.

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

**القيمة المعادة:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).