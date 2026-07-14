---
title: SmartArt
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک نمودار SmartArt
type: docs
url: /fa/com.aspose.slides/smartart/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

نمایانگر یک نمودار SmartArt
## متدها

| متد | توضیح |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Returns collections of all nodes in the SmartArt object. |
| [getNodes()](#getNodes--) | Returns collections of root nodes in SmartArt object. |
| [getLayout()](#getLayout--) | Returns or sets layout of the SmartArt object. |
| [setLayout(int value)](#setLayout-int-) | Returns or sets layout of the SmartArt object. |
| [getQuickStyle()](#getQuickStyle--) | Returns or sets quick style of SmartArt object. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Returns or sets quick style of SmartArt object. |
| [getColorStyle()](#getColorStyle--) | Returns or sets color style of SmartArt object. |
| [setColorStyle(int value)](#setColorStyle-int-) | Returns or sets color style of SmartArt object. |
| [isReversed()](#isReversed--) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
| [setReversed(boolean value)](#setReversed-boolean-) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

مجموعه‌ای از تمام گره‌ها در شیء SmartArt بازمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگرداندن:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

مجموعه‌ای از ریشه‌های گره در شیء SmartArt بازمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگرداندن:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```

طرح (layout) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**بازگرداندن:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

طرح (layout) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

سبک سریع (quick style) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**بازگرداندن:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

سبک سریع (quick style) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

سبک رنگ (color style) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**بازگرداندن:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

سبک رنگ (color style) شیء SmartArt را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

وضعیت نمودار SmartArt را نسبت به (چپ به راست) LTR یا (راست به چپ) RTL بازمی‌گرداند یا تنظیم می‌کند، اگر نمودار از وارون شدن پشتیبانی کند. قابل خواندن/نوشتن  boolean .

**بازگرداندن:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

وضعیت نمودار SmartArt را نسبت به (چپ به راست) LTR یا (راست به چپ) RTL بازمی‌گرداند یا تنظیم می‌کند، اگر نمودار از وارون شدن پشتیبانی کند. قابل خواندن/نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |