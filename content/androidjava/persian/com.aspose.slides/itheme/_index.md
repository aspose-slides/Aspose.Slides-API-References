---
title: ITheme
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک تم است.
type: docs
url: /fa/com.aspose.slides/itheme/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

نمایانگر یک تم است.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | طرح رنگ را برمی‌گرداند. |
| [getFontScheme()](#getFontScheme--) | طرح قلم را برمی‌گرداند. |
| [getFormatScheme()](#getFormatScheme--) | طرح قالب شکل را برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های تم مؤثر را با اعمال وراثت دریافت می‌کند. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


طرح رنگ را برمی‌گرداند. فقط خواندنی [IColorScheme](../../com.aspose.slides/icolorscheme).

**باز می‌گرداند:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


طرح قلم را برمی‌گرداند. فقط خواندنی [IFontScheme](../../com.aspose.slides/ifontscheme).

**باز می‌گرداند:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


طرح قالب شکل را برمی‌گرداند. فقط خواندنی [IFormatScheme](../../com.aspose.slides/iformatscheme).

**باز می‌گرداند:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


داده‌های تم مؤثر را با اعمال وراثت دریافت می‌کند.

**باز می‌گرداند:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - یک [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).