---
title: IThreeDFormat
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: خواص 3-بعدی را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ithreedformat/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

خواص 3-بعدی را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | مقدار یا تنظیم عرض یک کانتور 3D را باز می‌گرداند. |
| [setContourWidth(double value)](#setContourWidth-double-) | مقدار یا تنظیم عرض یک کانتور 3D را باز می‌گرداند. |
| [getExtrusionHeight()](#getExtrusionHeight--) | مقدار یا تنظیم ارتفاع اثر اکستروژن را باز می‌گرداند. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | مقدار یا تنظیم ارتفاع اثر اکستروژن را باز می‌گرداند. |
| [getDepth()](#getDepth--) | مقدار یا تنظیم عمق یک شکل 3D را باز می‌گرداند. |
| [setDepth(double value)](#setDepth-double-) | مقدار یا تنظیم عمق یک شکل 3D را باز می‌گرداند. |
| [getBevelTop()](#getBevelTop--) | مقدار یا تنظیم نوع یک برجستگی بالای 3D را باز می‌گرداند. |
| [getBevelBottom()](#getBevelBottom--) | مقدار یا تنظیم نوع یک برجستگی پایین 3D را باز می‌گرداند. |
| [getContourColor()](#getContourColor--) | مقدار یا تنظیم رنگ یک کانتور را باز می‌گرداند. |
| [getExtrusionColor()](#getExtrusionColor--) | مقدار یا تنظیم رنگ یک اکستروژن را باز می‌گرداند. |
| [getCamera()](#getCamera--) | مقدار یا تنظیم تنظیمات یک دوربین را باز می‌گرداند. |
| [getLightRig()](#getLightRig--) | مقدار یا تنظیم نوع یک نور را باز می‌گرداند. |
| [getMaterial()](#getMaterial--) | مقدار یا تنظیم نوع یک ماده را باز می‌گرداند. |
| [setMaterial(int value)](#setMaterial-int-) | مقدار یا تنظیم نوع یک ماده را باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی 3-بعدی مؤثر را با ارث‌برداری اعمال‌شده دریافت می‌کند. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

عرض یک کانتور 3D را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**باز می‌گرداند:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

عرض یک کانتور 3D را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

ارتفاع اثر اکستروژن را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**باز می‌گرداند:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

ارتفاع اثر اکستروژن را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

عمق یک شکل 3D را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**باز می‌گرداند:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

عمق یک شکل 3D را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

نوع یک برجستگی بالای 3D را باز می‌گرداند. فقط قابل خواندن [IShapeBevel](../../com.aspose.slides/ishapebevel).

**باز می‌گرداند:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

نوع یک برجستگی پایین 3D را باز می‌گرداند. فقط قابل خواندن [IShapeBevel](../../com.aspose.slides/ishapebevel).

**باز می‌گرداند:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

رنگ یک کانتور را باز می‌گرداند. فقط قابل خواندن [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

رنگ یک اکستروژن را باز می‌گرداند. فقط قابل خواندن [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

تنظیمات یک دوربین را باز می‌گرداند. فقط قابل خواندن [ICamera](../../com.aspose.slides/icamera).

**باز می‌گرداند:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

نوع یک نور را باز می‌گرداند. فقط قابل خواندن [ILightRig](../../com.aspose.slides/ilightrig).

**باز می‌گرداند:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

نوع یک ماده را باز می‌گرداند. قابل خواندن/نوشتن [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**باز می‌گرداند:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

نوع یک ماده را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی 3-بعدی مؤثر را با ارث‌برداری اعمال‌شده دریافت می‌کند.

**باز می‌گرداند:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - یک [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).