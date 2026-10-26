---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق التأثيرات الفعّالة.
type: docs
url: /ar/com.aspose.slides/ieffectformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق التأثيرات الفعّالة.

--------------------

هذا الواجهة تُستخدم مع الواجهة [IEffectFormat](../../com.aspose.slides/ieffectformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | يرجع true إذا تم تعطيل جميع التأثيرات (كما تم إنشاؤه للتو، كائن EffectFormat الافتراضي). |
| [getBlurEffect()](#getBlurEffect--) | تأثير الضبابية. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | تأثير تغطية التعبئة. |
| [getGlowEffect()](#getGlowEffect--) | تأثير التوهج. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | ظل داخلي. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | ظل خارجي. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | ظل مسبق الإعداد. |
| [getReflectionEffect()](#getReflectionEffect--) | انعكاس. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | حافة ناعمة. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

يرجع true إذا تم تعطيل جميع التأثيرات (كما تم إنشاؤه للتو، كائن EffectFormat الافتراضي). قيمة منطقية للقراءة فقط.

**Returns:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

تأثير الضبابية. قراءة فقط [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

**Returns:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

تأثير تغطية التعبئة. قراءة فقط [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

**Returns:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

تأثير التوهج. قراءة فقط [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

**Returns:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

ظل داخلي. قراءة فقط [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).

**Returns:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

ظل خارجي. قراءة فقط [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

**Returns:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

ظل مسبق الإعداد. قراءة فقط [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

**Returns:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

انعكاس. قراءة فقط [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

**Returns:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

حافة ناعمة. قراءة فقط [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

**Returns:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)