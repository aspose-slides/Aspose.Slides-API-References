---
title: IOverrideThemeManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ioverridethememanager/
---
**همه اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | تعیین می‌کند که آیا OverrideTheme تم مؤثر ارث‌برده را بازنویسی می‌کند یا نه. |
| [getOverrideTheme()](#getOverrideTheme--) | شیء تم بازنویسی‌کننده را برمی‌گرداند. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | شیء تم بازنویسی‌کننده را برمی‌گرداند. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

تعیین می‌کند که آیا OverrideTheme تم مؤثر ارث‌برده را بازنویسی می‌کند یا نه. برای فعال‌سازی OverrideTheme برای بازنویسی از متدهای OverrideTheme.Init\*() استفاده کنید. برای غیرفعال‌سازی OverrideTheme از بازنویسی از متد OverrideTheme.Clear() استفاده کنید. بولی فقط‌خواندنی.

**بازگشت:**  
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

شیء تم بازنویسی‌کننده را برمی‌گرداند. خواندنی/نوشتنی [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**بازگشت:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

شیء تم بازنویسی‌کننده را برمی‌گرداند. خواندنی/نوشتنی [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**پارامترها:**

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |