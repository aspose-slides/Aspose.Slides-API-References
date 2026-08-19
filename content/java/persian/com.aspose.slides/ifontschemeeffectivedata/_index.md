---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /fa/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر طرح‌فونت است.

--------------------

این رابط به‌عنوان بخشی از [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


پجمع فونت‌ها را برای بخش "body" اسلاید برمی‌گرداند. فقط خواندنی [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**بازگرداندن:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


پجمع فونت‌ها را برای بخش "heading" اسلاید برمی‌گرداند. فقط خواندنی [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**بازگرداندن:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


نام طرح‌فونت را برمی‌گرداند. فقط خواندنی String.

**بازگرداندن:**
java.lang.String