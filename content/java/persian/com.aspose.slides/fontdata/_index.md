---
title: FontData
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر تعریف یک قلم است.
type: docs
url: /fa/com.aspose.slides/fontdata/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

نمایانگر تعریف یک قلم است. غیرقابل تغییر.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | یک شیء FontData جدید با نام قلم مشخص شده ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getFontName()](#getFontName--) | نام قلم را برمی‌گرداند. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | نام قلم را برمی‌گرداند، به‌جای ارجاع تم، یک قلم واقعی استفاده شده را جایگزین می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا دو نمونه FontData برابر هستند یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند و برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
| [toString()](#toString--) | نمایش رشته‌ای را برمی‌گرداند. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

یک شیء FontData جدید با نام قلم مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام قلم. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

نام قلم را برمی‌گرداند. خواند/نوشت String.

**بازگشت:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

نام قلم را برمی‌گرداند، با جایگزینی ارجاع تم با یک قلم واقعی استفاده شده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | تمی که نام قلم تم‌دار از آن باید گرفته شود. تعیین مقدار صحیح به عهده فراخواننده است. ببینید [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**بازگشت:**
java.lang.String - نام قلم.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تشخیص می‌دهد آیا دو نمونه FontData برابر هستند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | FontData برای مقایسه با FontData فعلی. |

**بازگشت:**
boolean - **true** اگر FontData مشخص شده برابر با FontData فعلی باشد؛ در غیر این صورت، **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند و برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است.

**بازگشت:**
int - کد هش FontData.
### toString() {#toString--}
```
public String toString()
```

نمایش رشته‌ای را برمی‌گرداند.

**بازگشت:**
java.lang.String - نمایش رشته‌ای.