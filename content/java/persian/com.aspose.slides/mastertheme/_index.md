---
title: MasterTheme
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک قالب اصلی است.
type: docs
url: /fa/com.aspose.slides/mastertheme/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

نمایانگر یک قالب اصلی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | طرح رنگ را برمی‌گرداند. |
| [getFontScheme()](#getFontScheme--) | طرح قلم را برمی‌گرداند. |
| [getFormatScheme()](#getFormatScheme--) | طرح قالب شکل را برمی‌گرداند. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | مجموعه‌ای از طرح‌های رنگی اضافی را برمی‌گرداند. |
| [getName()](#getName--) | نام یک قالب را برمی‌گرداند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک قالب را برمی‌گرداند. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

طرح رنگ را برمی‌گرداند. فقط خواندنی [IColorScheme](../../com.aspose.slides/icolorscheme).

**بازگشت:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

طرح قلم را برمی‌گرداند. فقط خواندنی [IFontScheme](../../com.aspose.slides/ifontscheme).

**بازگشت:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

طرح قالب شکل را برمی‌گرداند. فقط خواندنی [IFormatScheme](../../com.aspose.slides/iformatscheme).

**بازگشت:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

مجموعه‌ای از طرح‌های رنگی اضافی را برمی‌گرداند. این طرح‌ها بر ظاهر ارائه تأثیری ندارند، می‌توانند به‌عنوان طرح رنگ اصلی برای یک اسلاید انتخاب شوند. فقط خواندنی [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**بازگشت:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

نام یک قالب را برمی‌گرداند. قابل خواندن و نوشتن String.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

نام یک قالب را برمی‌گرداند. قابل خواندن و نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**
long