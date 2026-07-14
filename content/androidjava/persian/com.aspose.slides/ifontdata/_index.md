---
title: IFontData
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک تعریف قلم را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

یک تعریف قلم را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontName()](#getFontName--) | نام قلم را بازمی‌گرداند. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | نام قلم را بازمی‌گرداند و مرجع تم را با قلم واقعی استفاده‌شده جایگزین می‌کند. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

نام قلم را بازمی‌گرداند. فقط‌قابل‌خواندن String.

**باز می‌گردد:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

نام قلم را بازمی‌گرداند و مرجع تم را با قلم واقعی استفاده‌شده جایگزین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | تم‌ای که نام قلم تم‌دار باید از آن گرفته شود. ارائه مقدار صحیح به عهدهٔ فراخواننده است. |

**باز می‌گردد:**
java.lang.String - نام قلم.