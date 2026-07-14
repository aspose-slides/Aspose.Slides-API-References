---
title: IBlur
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک افکت تاری است که بر کل شکل، از جمله پرش آن، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/iblur/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

نمایانگر یک افکت تاری است که بر کل شکل، شامل پرش آن، اعمال می‌شود. تمام کانال‌های رنگ، از جمله آلفا، تحت تأثیر قرار می‌گیرند.

## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Returns or sets blur radius. خواندنی/نوشتنی double.

**بازگرداندن:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Returns or sets blur radius. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. خواندنی/نوشتنی boolean.

**بازگرداندن:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |