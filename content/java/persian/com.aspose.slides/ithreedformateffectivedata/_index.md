---
title: IThreeDFormatEffectiveData
second_title: مرجع API Aspose.Slides برای Java
description: شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی ۳-بعدی مؤثر را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ithreedformateffectivedata/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی ۳-بعدی مؤثر را نشان می‌دهد.

--------------------

این واسط همراه با واسط [IThreeDFormat](../../com.aspose.slides/ithreedformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | عرض یک محدودهٔ ۳-بعدی را بازمی‌گرداند. |
| [getExtrusionHeight()](#getExtrusionHeight--) | ارتفاع اثر برآمدگی را بازمی‌گرداند. |
| [getDepth()](#getDepth--) | عمق یک شکل ۳-بعدی را بازمی‌گرداند. |
| [getBevelTop()](#getBevelTop--) | نوع برجستگی بالایی ۳-بعدی را بازمی‌گرداند. |
| [getBevelBottom()](#getBevelBottom--) | نوع برجستگی پایینی ۳-بعدی را بازمی‌گرداند. |
| [getContourColor()](#getContourColor--) | رنگ یک محدوده را بازمی‌گرداند. |
| [getExtrusionColor()](#getExtrusionColor--) | رنگ یک برآمدگی را بازمی‌گرداند. |
| [getCamera()](#getCamera--) | تنظیمات یک دوربین را بازمی‌گرداند. |
| [getLightRig()](#getLightRig--) | نوع یک نور را بازمی‌گرداند. |
| [getMaterial()](#getMaterial--) | نوع یک ماده را بازمی‌گرداند. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

بازمی‌گرداند عرض یک محدودهٔ ۳-بعدی. double فقط‌خواندنی.

**بازمی‌گرداند:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

بازمی‌گرداند ارتفاع اثر برآمدگی. double فقط‌خواندنی.

**بازمی‌گرداند:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

بازمی‌گرداند عمق یک شکل ۳-بعدی. double فقط‌خواندنی.

**بازمی‌گرداند:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

بازمی‌گرداند نوع برجستگی بالایی ۳-بعدی. [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata) فقط‌خواندنی.

**بازمی‌گرداند:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

بازمی‌گرداند نوع برجستگی پایینی ۳-بعدی. [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata) فقط‌خواندنی.

**بازمی‌گرداند:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

بازمی‌گرداند رنگ یک محدوده. java.awt.Color فقط‌خواندنی.

**بازمی‌گرداند:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

بازمی‌گرداند رنگ یک برآمدگی. java.awt.Color فقط‌خواندنی.

**بازمی‌گرداند:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

بازمی‌گرداند تنظیمات یک دوربین. [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata) فقط‌خواندنی.

**بازمی‌گرداند:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

بازمی‌گرداند نوع یک نور. [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata) فقط‌خواندنی.

**بازمی‌گرداند:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

بازمی‌گرداند نوع یک ماده. [MaterialPresetType](../../com.aspose.slides/materialpresettype) فقط‌خواندنی.

**بازمی‌گرداند:**
int