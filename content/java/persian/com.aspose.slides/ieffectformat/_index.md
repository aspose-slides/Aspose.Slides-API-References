---
title: IEffectFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر ویژگی‌های اثر شکل.
type: docs
url: /fa/com.aspose.slides/ieffectformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Represents effect properties of shape.
## متدها

| متد | توضیح |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | در صورتی که تمام اثرها غیرفعال باشند (همانند شیء EffectFormat پیش‌فرض که تازه ساخته شده)، مقدار true برمی‌گرداند. |
| [getBlurEffect()](#getBlurEffect--) | اثر تاری. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | اثر تاری. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | اثر پوشش پر کردن. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | اثر پوشش پر کردن. |
| [getGlowEffect()](#getGlowEffect--) | اثر درخشندگی. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | اثر درخشندگی. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | سایه داخلی. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | سایه داخلی. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | سایه خارجی. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | سایه خارجی. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | سایه پیش‌تنظیم. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | سایه پیش‌تنظیم. |
| [getReflectionEffect()](#getReflectionEffect--) | بازتاب. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | بازتاب. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | حاشیه نرم. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | حاشیه نرم. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | اثر تاری را تنظیم می‌کند. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | اثر پوشش پر کردن را فعال می‌کند. |
| [enableGlowEffect()](#enableGlowEffect--) | اثر درخشندگی را فعال می‌کند. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | سایه داخلی را فعال می‌کند. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | سایه خارجی را فعال می‌کند. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | سایه‌های پیش‌تنظیم را فعال می‌کند. |
| [enableReflectionEffect()](#enableReflectionEffect--) | اثر بازتاب را فعال می‌کند. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | حاشیه نرم را فعال می‌کند. |
| [disableBlurEffect()](#disableBlurEffect--) | اثر تاری را غیرفعال می‌کند. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | اثر پوشش پر کردن را غیرفعال می‌کند. |
| [disableGlowEffect()](#disableGlowEffect--) | اثر درخشندگی را غیرفعال می‌کند. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | سایه داخلی را غیرفعال می‌کند. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | سایه خارجی را غیرفعال می‌کند. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | سایه پیش‌تنظیم را غیرفعال می‌کند. |
| [disableReflectionEffect()](#disableReflectionEffect--) | اثر بازتاب را غیرفعال می‌کند. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | حاشیه نرم را غیرفعال می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی اثر مؤثر را با اعمال ارث‌گیری دریافت می‌کند. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

در صورتی که تمام اثرها غیرفعال باشند (همانند شیء EffectFormat پیش‌فرض که تازه ساخته شده)، مقدار true برمی‌گرداند. Boolean فقط-خواندنی.

**بازگشت:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

اثر تاری. قابل خواندن/نوشتن [IBlur](../../com.aspose.slides/iblur).

**بازگشت:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

اثر تاری. قابل خواندن/نوشتن [IBlur](../../com.aspose.slides/iblur).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

اثر پوشش پر کردن. قابل خواندن/نوشتن [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**بازگشت:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

اثر پوشش پر کردن. قابل خواندن/نوشتن [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

اثر درخشندگی. قابل خواندن/نوشتن [IGlow](../../com.aspose.slides/iglow).

**بازگشت:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

اثر درخشندگی. قابل خواندن/نوشتن [IGlow](../../com.aspose.slides/iglow).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

سایه داخلی. قابل خواندن/نوشتن [IInnerShadow](../../com.aspose.slides/iinnershadow).

**بازگشت:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

سایه داخلی. قابل خواندن/نوشتن [IInnerShadow](../../com.aspose.slides/iinnershadow).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

سایه خارجی. قابل خواندن/نوشتن [IOuterShadow](../../com.aspose.slides/ioutershadow).

**بازگشت:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

سایه خارجی. قابل خواندن/نوشتن [IOuterShadow](../../com.aspose.slides/ioutershadow).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

سایه پیش‌تنظیم. قابل خواندن/نوشتن [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**بازگشت:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

سایه پیش‌تنظیم. قابل خواندن/نوشتن [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

بازتاب. قابل خواندن/نوشتن [IReflection](../../com.aspose.slides/ireflection).

**بازگشت:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

بازتاب. قابل خواندن/نوشتن [IReflection](../../com.aspose.slides/ireflection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

حاشیه نرم. قابل خواندن/نوشتن [ISoftEdge](../../com.aspose.slides/isoftedge).

**بازگشت:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

حاشیه نرم. قابل خواندن/نوشتن [ISoftEdge](../../com.aspose.slides/isoftedge).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

اثر تاری را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع. |
| grow | boolean | رشد. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

اثر پوشش پر کردن را فعال می‌کند.
### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

اثر درخشندگی را فعال می‌کند.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

سایه داخلی را فعال می‌کند.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

سایه خارجی را فعال می‌کند.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

سایه‌های پیش‌تنظیم را فعال می‌کند.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

اثر بازتاب را فعال می‌کند.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

حاشیه نرم را فعال می‌کند.
### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

اثر تاری را غیرفعال می‌کند.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

اثر پوشش پر کردن را غیرفعال می‌کند.
### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

اثر درخشندگی را غیرفعال می‌کند.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

سایه داخلی را غیرفعال می‌کند.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

سایه خارجی را غیرفعال می‌کند.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

سایه پیش‌تنظیم را غیرفعال می‌کند.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

اثر بازتاب را غیرفعال می‌کند.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

حاشیه نرم را غیرفعال می‌کند.
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی اثر مؤثر را با اعمال ارث‌گیری دریافت می‌کند.

**بازگشت:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).