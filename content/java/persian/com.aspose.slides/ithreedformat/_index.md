---
title: IThreeDFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر خصوصیات 3-بعدی.
type: docs
url: /fa/com.aspose.slides/ithreedformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

نمایانگر خصوصیات 3-بعدی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setContourWidth(double value)](#setContourWidth-double-) | عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getExtrusionHeight()](#getExtrusionHeight--) | ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getDepth()](#getDepth--) | عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setDepth(double value)](#setDepth-double-) | عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getBevelTop()](#getBevelTop--) | نوع برش بالا (top) یک bevel 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getBevelBottom()](#getBevelBottom--) | نوع برش پایین (bottom) یک bevel 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getContourColor()](#getContourColor--) | رنگ یک کانتور را برمی‌گرداند یا تنظیم می‌کند. |
| [getExtrusionColor()](#getExtrusionColor--) | رنگ یک برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getCamera()](#getCamera--) | تنظیمات یک دوربین را برمی‌گرداند یا تنظیم می‌کند. |
| [getLightRig()](#getLightRig--) | نوع یک نور را برمی‌گرداند یا تنظیم می‌کند. |
| [getMaterial()](#getMaterial--) | نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. |
| [setMaterial(int value)](#setMaterial-int-) | نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی 3-بعدی مؤثر را با اعمال ارث‌بری می‌گیرد. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

نوع برش بالا (top) یک bevel 3D را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [IShapeBevel](../../com.aspose.slides/ishapebevel).

**بازگشت:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

نوع برش پایین (bottom) یک bevel 3D را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [IShapeBevel](../../com.aspose.slides/ishapebevel).

**بازگشت:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

رنگ یک کانتور را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

رنگ یک برآمدگی را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

تنظیمات یک دوربین را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [ICamera](../../com.aspose.slides/icamera).

**بازگشت:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

نوع یک نور را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [ILightRig](../../com.aspose.slides/ilightrig).

**بازگشت:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**بازگشت:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی 3-بعدی مؤثر را با اعمال ارث‌بری می‌گیرد.

**بازگشت:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).