---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /fa/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

شیء غیرقابل تغییر که دارای ویژگی‌های مؤثر تم است.

--------------------

این رابط همراه با رابط [ITheme](../../com.aspose.slides/itheme) برای برگرداندن مقادیر قالب‌بندی مؤثر با به‌کارگیری وراثت استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | طرح رنگ را برمی‌گرداند. |
| [getFontScheme()](#getFontScheme--) | طرح قلم را برمی‌گرداند. |
| [getFormatScheme()](#getFormatScheme--) | طرح قالب‌ شکل را برمی‌گرداند. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

طرح رنگ را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | java.lang.Integer | رنگ java.lang.Integer |

**بازگشت:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - طرح رنگ [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

طرح قلم را برمی‌گرداند. فقط‌خواندنی [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**بازگشت:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

طرح قالب‌ شکل را برمی‌گرداند. فقط‌خواندنی [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**بازگشت:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)