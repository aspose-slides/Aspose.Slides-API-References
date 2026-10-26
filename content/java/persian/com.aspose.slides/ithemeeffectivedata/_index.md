---
title: IThemeEffectiveData
second_title: Aspose.Slides برای مرجع API جاوا
description: شیء ثابت که شامل ویژگی‌های مؤثر تم است.
type: docs
url: /fa/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

شیء ثابت که شامل ویژگی‌های مؤثر تم است.

--------------------

این اینترفیس همراه با اینترفیس [ITheme](../../com.aspose.slides/itheme) استفاده می‌شود تا مقادیر قالب‌بندی مؤثر با ارث‌بری اعمال‌شده بازگردانده شود.

## متدها

| متد | توضیح |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | طرح رنگ را برمی‌گرداند. |
| [getFontScheme()](#getFontScheme--) | طرح قلم را برمی‌گرداند. |
| [getFormatScheme()](#getFormatScheme--) | طرح قالب شکل را برمی‌گرداند. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

طرح رنگ را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**بازگشت:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - طرح رنگ [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

طرح قلم را برمی‌گرداند. فقط-خواندنی [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**بازگشت:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

طرح قالب شکل را برمی‌گرداند. فقط-خواندنی [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**بازگشت:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)