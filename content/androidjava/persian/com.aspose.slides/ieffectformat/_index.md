---
title: IEffectFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: ویژگی‌های اثر یک شکل را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ieffectformat/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

نمایندهٔ ویژگی‌های اثر یک شکل است.
## متدها

| متد | توضیح |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | در صورتی که همهٔ اثرها غیرفعال باشند (مانند شیء EffectFormat پیش‌فرض تازه ایجاد شده) مقدار true برمی‌گرداند. |
| [getBlurEffect()](#getBlurEffect--) | اثر محو. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | اثر محو. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | اثر پوشش پر کردن. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | اثر پوشش پر کردن. |
| [getGlowEffect()](#getGlowEffect--) | اثر درخشش. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | اثر درخشش. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | سایه داخلی. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | سایه داخلی. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | سایه بیرونی. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | سایه بیرونی. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | سایه پیش‌تنظیم‌شده. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | سایه پیش‌تنظیم‌شده. |
| [getReflectionEffect()](#getReflectionEffect--) | انعکاس. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | انعکاس. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | لبه نرم. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | لبه نرم. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | اثر محو را تنظیم می‌کند. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | اثر پوشش پر کردن را فعال می‌کند. |
| [enableGlowEffect()](#enableGlowEffect--) | اثر درخشش را فعال می‌کند. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | اثر سایه داخلی را فعال می‌کند. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | اثر سایه بیرونی را فعال می‌کند. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | اثر سایه‌های پیش‌تنظیم‌شده را فعال می‌کند. |
| [enableReflectionEffect()](#enableReflectionEffect--) | اثر انعکاس را فعال می‌کند. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | اثر لبه نرم را فعال می‌کند. |
| [disableBlurEffect()](#disableBlurEffect--) | اثر محو را غیرفعال می‌کند. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | اثر پوشش پر کردن را غیرفعال می‌کند. |
| [disableGlowEffect()](#disableGlowEffect--) | اثر درخشش را غیرفعال می‌کند. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | اثر سایه داخلی را غیرفعال می‌کند. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | اثر سایه بیرونی را غیرفعال می‌کند. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | اثر سایه پیش‌تنظیم‌شده را غیرفعال می‌کند. |
| [disableReflectionEffect()](#disableReflectionEffect--) | اثر انعکاس را غیرفعال می‌کند. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | اثر لبه نرم را غیرفعال می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر اثر را با اعمال ارث‌بری دریافت می‌کند. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

در صورتی که همهٔ اثرها غیرفعال باشند (مانند شیء EffectFormat پیش‌فرض تازه ایجاد شده) مقدار true برمی‌گرداند. بولی فقط-خواندنی.

**بازمی‌گرداند:**  
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

اثر محو. قابل خواندن/نوشتن [IBlur](../../com.aspose.slides/iblur).

**بازمی‌گرداند:**  
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

اثر محو. قابل خواندن/نوشتن [IBlur](../../com.aspose.slides/iblur).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

اثر پوشش پر کردن. قابل خواندن/نوشتن [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**بازمی‌گرداند:**  
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

اثر درخشش. قابل خواندن/نوشتن [IGlow](../../com.aspose.slides/iglow).

**بازمی‌گرداند:**  
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

اثر درخشش. قابل خواندن/نوشتن [IGlow](../../com.aspose.slides/iglow).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

سایه داخلی. قابل خواندن/نوشتن [IInnerShadow](../../com.aspose.slides/iinnershadow).

**بازمی‌گرداند:**  
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

سایه بیرونی. قابل خواندن/نوشتن [IOuterShadow](../../com.aspose.slides/ioutershadow).

**بازمی‌گرداند:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

سایه بیرونی. قابل خواندن/نوشتن [IOuterShadow](../../com.aspose.slides/ioutershadow).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

سایه پیش‌تنظیم‌شده. قابل خواندن/نوشتن [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**بازمی‌گرداند:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

سایه پیش‌تنظیم‌شده. قابل خواندن/نوشتن [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

انعکاس. قابل خواندن/نوشتن [IReflection](../../com.aspose.slides/ireflection).

**بازمی‌گرداند:**  
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

انعکاس. قابل خواندن/نوشتن [IReflection](../../com.aspose.slides/ireflection).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

لبه نرم. قابل خواندن/نوشتن [ISoftEdge](../../com.aspose.slides/isoftedge).

**بازمی‌گرداند:**  
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

لبه نرم. قابل خواندن/نوشتن [ISoftEdge](../../com.aspose.slides/isoftedge).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

اثر محو را تنظیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع. |
| grow | boolean | گسترش. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

اثر پوشش پر کردن را فعال می‌کند.
### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

اثر درخشش را فعال می‌کند.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

اثر سایه داخلی را فعال می‌کند.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

اثر سایه بیرونی را فعال می‌کند.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

اثر سایه‌های پیش‌تنظیم‌شده را فعال می‌کند.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

اثر انعکاس را فعال می‌کند.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

اثر لبه نرم را فعال می‌کند.
### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

اثر محو را غیرفعال می‌کند.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

اثر پوشش پر کردن را غیرفعال می‌کند.
### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

اثر درخشش را غیرفعال می‌کند.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

اثر سایه داخلی را غیرفعال می‌کند.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

اثر سایه بیرونی را غیرفعال می‌کند.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

اثر سایه پیش‌تنظیم‌شده را غیرفعال می‌کند.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

اثر انعکاس را غیرفعال می‌کند.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

اثر لبه نرم را غیرفعال می‌کند.
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر اثر را با اعمال ارث‌بری دریافت می‌کند.

**بازمی‌گرداند:**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - یک [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).