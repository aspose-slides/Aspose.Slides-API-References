---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /fa/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

نمایش یک تعریف فونت.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontName()](#getFontName--) | نام فونت را برمی‌گرداند. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | نام فونت را برمی‌گرداند، با جایگزینی ارجاع تم با فونت واقعی استفاده‌شده. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

نام فونت را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

نام فونت را برمی‌گرداند، با جایگزینی ارجاع تم با فونت واقعی استفاده‌شده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | تمی که نام فونت موضوعی باید از آن گرفته شود. ارائه مقدار صحیح به عهده فراخواننده است. |

**بازگشت:**
java.lang.String - Font name.