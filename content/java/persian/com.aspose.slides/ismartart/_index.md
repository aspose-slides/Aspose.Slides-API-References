---
title: ISmartArt
second_title: مرجع API Aspose.Slides برای جاوا
description: یک نمودار SmartArt را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ismartart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

نمایش یک نمودار SmartArt.
## متدها

| متد | توضیح |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | مجموعه‌ای از تمام گره‌های موجود در شیء SmartArt را برمی‌گرداند. |
| [getNodes()](#getNodes--) | مجموعه‌ای از گره‌های ریشه در شیء SmartArt را برمی‌گرداند. |
| [getLayout()](#getLayout--) | چیدمان شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [setLayout(int value)](#setLayout-int-) | چیدمان شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [getQuickStyle()](#getQuickStyle--) | سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [getColorStyle()](#getColorStyle--) | سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [setColorStyle(int value)](#setColorStyle-int-) | سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. |
| [isReversed()](#isReversed--) | وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، در صورتی که نمودار از معکوس‌سازی پشتیبانی کند. |
| [setReversed(boolean value)](#setReversed-boolean-) | وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، در صورتی که نمودار از معکوس‌سازی پشتیبانی کند. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

مجموعه‌ای از تمام گره‌های موجود در شیء SmartArt را برمی‌گرداند. فقط-خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

مجموعه‌ای از گره‌های ریشه در شیء SmartArt را برمی‌گرداند. فقط-خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

چیدمان شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**بازگشت:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

چیدمان شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**بازگشت:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**بازگشت:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، در صورتی که نمودار از معکوس‌سازی پشتیبانی کند. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، در صورتی که نمودار از معکوس‌سازی پشتیبانی کند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |