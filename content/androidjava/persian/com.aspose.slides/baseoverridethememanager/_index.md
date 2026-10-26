---
title: BaseOverrideThemeManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس پایه برای کلاس‌هایی که دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کنند.
type: docs
url: /fa/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

کلاس پایه برای کلاس‌هایی که دسترسی به انواع مختلف تم‌های بازنویسی‌شده را فراهم می‌کنند.
## متدها

| Method | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | شیء تم بازنویسی‌شده را برمی‌گرداند. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | شیء تم بازنویسی‌شده را برمی‌گرداند. |
| [createThemeEffective()](#createThemeEffective--) | شیء تم را برمی‌گرداند. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | تعیین می‌کند که آیا OverrideTheme تم مؤثر به ارث‌برده را بازنویسی می‌کند یا نه. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | یک طرح رنگی اضافی را به اسلاید اعمال می‌کند. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


شیء تم بازنویسی‌شده را برمی‌گرداند. قابل مطالعه/نوشتن [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**بازگشت:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


شیء تم بازنویسی‌شده را برمی‌گرداند. قابل مطالعه/نوشتن [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


شیء تم را برمی‌گرداند.

**بازگشت:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


تعیین می‌کند که آیا OverrideTheme تم مؤثر به ارث‌برده را بازنویسی می‌کند یا خیر. برای فعال‌سازی OverrideTheme برای بازنویسی از متدهای OverrideTheme.Init*() استفاده کنید. برای غیرفعال‌سازی OverrideTheme از بازنویسی از متد OverrideTheme.Clear() استفاده کنید. فقط-خواندنی boolean.

**بازگشت:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


یک طرح رنگی اضافی را به اسلاید اعمال می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | شیء [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |