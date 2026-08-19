---
title: IOverrideThemeManager
second_title: مرجع API Aspose.Slides برای جاوا
description: دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ioverridethememanager/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | تعیین می‌کند که OverrideTheme تم مؤثر به ارث‌برده را بازنویسی می‌کند یا نه. |
| [getOverrideTheme()](#getOverrideTheme--) | شیء تم بازنویسی‌شده را بر می‌گرداند. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | شیء تم بازنویسی‌شده را بر می‌گرداند. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


تعیین می‌کند که OverrideTheme تم مؤثر به ارث‌برده را بازنویسی می‌کند یا نه. برای فعال‌سازی OverrideTheme برای بازنویسی از متدهای OverrideTheme.Init\*() استفاده کنید. برای غیرفعال‌سازی OverrideTheme از بازنویسی از متد OverrideTheme.Clear() استفاده کنید. **فقط-خواندنی** boolean.

**بازگرداندن:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


شیء تم را بر می‌گرداند. **خواندنی/نوشتنی** [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**بازگرداندن:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


شیء تم را بر می‌گرداند. **خواندنی/نوشتنی** [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |