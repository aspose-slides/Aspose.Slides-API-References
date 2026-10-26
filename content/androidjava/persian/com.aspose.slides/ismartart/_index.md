---
title: ISmartArt
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: نمایانگر یک نمودار SmartArt است.
type: docs
url: /fa/com.aspose.slides/ismartart/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

نمایانگر یک نمودار SmartArt است.
## متدها

| متد | توضیح |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | مجموعه‌ای از تمام گره‌ها در شیء SmartArt را بازمی‌گرداند. |
| [getNodes()](#getNodes--) | مجموعه‌ای از گره‌های ریشه در شیء SmartArt را بازمی‌گرداند. |
| [getLayout()](#getLayout--) | دریافت یا تنظیم طرح‌بندی شیء SmartArt. |
| [setLayout(int value)](#setLayout-int-) | دریافت یا تنظیم طرح‌بندی شیء SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | دریافت یا تنظیم سبک سریع شیء SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | دریافت یا تنظیم سبک سریع شیء SmartArt. |
| [getColorStyle()](#getColorStyle--) | دریافت یا تنظیم سبک رنگی شیء SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | دریافت یا تنظیم سبک رنگی شیء SmartArt. |
| [isReversed()](#isReversed--) | دریافت یا تنظیم وضعیت نمودار SmartArt نسبت به (چپ به راست) LTR یا (راست به چپ) RTL، اگر نمودار از معکوس شدن پشتیبانی کند. |
| [setReversed(boolean value)](#setReversed-boolean-) | دریافت یا تنظیم وضعیت نمودار SmartArt نسبت به (چپ به راست) LTR یا (راست به چپ) RTL، اگر نمودار از معکوس شدن پشتیبانی کند. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

مجموعه‌ای از تمام گره‌ها در شیء SmartArt را بازمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

مجموعه‌ای از گره‌های ریشه در شیء SmartArt را بازمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

دریافت یا تنظیم طرح‌بندی شیء SmartArt. خواندنی/نوشتنی [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**بازگشت:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

دریافت یا تنظیم طرح‌بندی شیء SmartArt. خواندنی/نوشتنی [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

دریافت یا تنظیم سبک سریع شیء SmartArt. خواندنی/نوشتنی [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**بازگشت:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

دریافت یا تنظیم سبک سریع شیء SmartArt. خواندنی/نوشتنی [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

دریافت یا تنظیم سبک رنگی شیء SmartArt. خواندنی/نوشتنی [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**بازگشت:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

دریافت یا تنظیم سبک رنگی شیء SmartArt. خواندنی/نوشتنی [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

دریافت یا تنظیم وضعیت نمودار SmartArt نسبت به (چپ به راست) LTR یا (راست به چپ) RTL، اگر نمودار از معکوس شدن پشتیبانی کند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

دریافت یا تنظیم وضعیت نمودار SmartArt نسبت به (چپ به راست) LTR یا (راست به چپ) RTL، اگر نمودار از معکوس شدن پشتیبانی کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |