---
title: BaseOverrideThemeManager
second_title: Aspose.Slides برای مرجع API جاوا
description: کلاس پایه‌ای برای کلاس‌هایی که دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کنند.
type: docs
url: /fa/com.aspose.slides/baseoverridethememanager/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

کلاس پایه‌ای برای کلاس‌هایی که دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | شی تم بازنویسی‌شده را برمی‌گرداند. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | شی تم بازنویسی‌شده را برمی‌گرداند. |
| [createThemeEffective()](#createThemeEffective--) | شی تم را برمی‌گرداند. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | تعیین می‌کند که آیا OverrideTheme تم مؤثر به‌ارث‌برده را بازنویسی می‌کند یا خیر. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | طرح رنگی اضافی را بر روی یک اسلاید اعمال می‌کند. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

شی تم بازنویسی‌شده را برمی‌گرداند. خواندنی/نوشتنی [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**بازگشت:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

شی تم بازنویسی‌شده را برمی‌گرداند. خواندنی/نوشتنی [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

شی تم را برمی‌گرداند.

**بازگشت:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

تعیین می‌کند که آیا OverrideTheme تم مؤثر به‌ارث‌برده را بازنویسی می‌کند یا خیر. برای فعال‌سازی OverrideTheme برای بازنویسی از متدهای OverrideTheme.Init\*() استفاده کنید. برای غیرفعال‌سازی OverrideTheme از بازنویسی از متد OverrideTheme.Clear() استفاده کنید. بولی فقط-خواندنی.

**بازگشت:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

طرح رنگی اضافی را بر روی یک اسلاید اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | شی [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |