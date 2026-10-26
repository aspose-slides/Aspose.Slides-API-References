---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که ویژگی‌های فرمت‌بندی سه‌بعدی مؤثر را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ithreedformateffectivedata/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

شیء غیرقابل تغییر که ویژگی‌های فرمت‌بندی سه‌بعدی مؤثر را نمایندگی می‌کند.

--------------------

این رابط همراه با رابط [IThreeDFormat](../../com.aspose.slides/ithreedformat) برای بازگرداندن مقادیر فرمت‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | عرض یک کانتور سه‌بعدی را برمی‌گرداند. |
| [getExtrusionHeight()](#getExtrusionHeight--) | ارتفاع یک اثر برجستگی را برمی‌گرداند. |
| [getDepth()](#getDepth--) | عمق یک شکل سه‌بعدی را برمی‌گرداند. |
| [getBevelTop()](#getBevelTop--) | نوع برش بالایی سه‌بعدی را برمی‌گرداند. |
| [getBevelBottom()](#getBevelBottom--) | نوع برش پایینی سه‌بعدی را برمی‌گرداند. |
| [getContourColor()](#getContourColor--) | رنگ یک کانتور را برمی‌گرداند. |
| [getExtrusionColor()](#getExtrusionColor--) | رنگ یک برجستگی را برمی‌گرداند. |
| [getCamera()](#getCamera--) | تنظیمات یک دوربین را برمی‌گرداند. |
| [getLightRig()](#getLightRig--) | نوع نوری را برمی‌گرداند. |
| [getMaterial()](#getMaterial--) | نوع یک ماده را برمی‌گرداند. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

عرض یک کانتور سه‌بعدی را برمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**  
double

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

ارتفاع یک اثر برجستگی را برمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**  
double

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

عمق یک شکل سه‌بعدی را برمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**  
double

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

نوع برش بالایی سه‌بعدی را برمی‌گرداند. فقط-خواندنی [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**بازمی‌گرداند:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

نوع برش پایینی سه‌بعدی را برمی‌گرداند. فقط-خواندنی [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**بازمی‌گرداند:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

رنگ یک کانتور را برمی‌گرداند. فقط-خواندنی java.lang.Integer.

**بازمی‌گرداند:**  
java.lang.Integer

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

رنگ یک برجستگی را برمی‌گرداند. فقط-خواندنی java.lang.Integer.

**بازمی‌گرداند:**  
java.lang.Integer

### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

تنظیمات یک دوربین را برمی‌گرداند. فقط-خواندنی [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**بازمی‌گرداند:**  
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)

### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

نوع نوری را برمی‌گرداند. فقط-خواندنی [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**بازمی‌گرداند:**  
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

نوع یک ماده را برمی‌گرداند. فقط-خواندنی [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**بازمی‌گرداند:**  
int