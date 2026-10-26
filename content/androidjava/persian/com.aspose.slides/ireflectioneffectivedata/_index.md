---
title: IReflectionEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که اثر انعکاس را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ireflectioneffectivedata/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

شیء غیرقابل تغییر که اثر انعکاس را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای اولیه (درصد) را مشخص می‌کند. |
| [getEndPosAlpha()](#getEndPosAlpha--) | موقعیت پایان (در طول مسیر گرادیان آلفا) مقدار آلفای نهایی (درصد) را مشخص می‌کند. |
| [getFadeDirection()](#getFadeDirection--) | جهت جابه‌جایی انعکاس را مشخص می‌کند. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | شفافیت اولیه انعکاس. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | شفافیت نهایی انعکاس. |
| [getBlurRadius()](#getBlurRadius--) | شعاع تاری. |
| [getDirection()](#getDirection--) | جهت انعکاس. |
| [getDistance()](#getDistance--) | فاصله انعکاس. |
| [getRectangleAlign()](#getRectangleAlign--) | تراز مستطیل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاویه کج‌کاری افقی را مشخص می‌کند. |
| [getSkewVertical()](#getSkewVertical--) | زاویه کج‌کاری عمودی را مشخص می‌کند. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | مشخص می‌کند آیا انعکاس باید با شکل در صورت چرخش شکل، چرخانده شود یا نه. |
| [getScaleHorizontal()](#getScaleHorizontal--) | فاکتور مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌گردد. |
| [getScaleVertical()](#getScaleVertical--) | فاکتور مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌گردد. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```


موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای اولیه (درصد) را مشخص می‌کند. فقط‌خواندنی float.

**بازگشت:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```


موقعیت پایان (در طول مسیر گرادیان آلفا) مقدار آلفای نهایی (درصد) را مشخص می‌کند. فقط‌خواندنی float.

**بازگشت:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```


جهت جابه‌جایی انعکاس را مشخص می‌کند. (زاویه) فقط‌خواندنی float.

**بازگشت:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```


شفافیت اولیه انعکاس. (درصد) فقط‌خواندنی float.

**بازگشت:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```


شفافیت نهایی انعکاس. (درصد) فقط‌خواندنی float.

**بازگشت:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


شعاع تاری. فقط‌خواندنی double.

**بازگشت:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


جهت انعکاس. فقط‌خواندنی float.

**بازگشت:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


فاصله انعکاس. فقط‌خواندنی double.

**بازگشت:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


تراز مستطیل. فقط‌خواندنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**بازگشت:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


زاویه کج‌کاری افقی را مشخص می‌کند. فقط‌خواندنی double.

**بازگشت:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


زاویه کج‌کاری عمودی را مشخص می‌کند. فقط‌خواندنی double.

**بازگشت:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


مشخص می‌کند آیا انعکاس باید با شکل در صورت چرخش شکل، چرخانده شود یا نه. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


فاکتور مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌گیرد. (درصد) فقط‌خواندنی double.

**بازگشت:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


فاکتور مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌گیرد. (درصد) فقط‌خواندنی double.

**بازگشت:**
double