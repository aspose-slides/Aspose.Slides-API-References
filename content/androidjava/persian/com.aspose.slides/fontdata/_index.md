---
title: FontData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک تعریف قلم است.
type: docs
url: /fa/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

نمایانگر تعریف یک قلم است. غیرقابل تغییر.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | یک شی FontData جدید با نام قلم مشخص‌شده ایجاد می‌کند. |
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | نام قلم را برمی‌گرداند. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | نام قلم را برمی‌گرداند و مرجع تم را با قلم واقعی استفاده‌شده جایگزین می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا دو نمونه FontData برابر هستند یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای نوعی خاص عمل می‌کند و برای الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
| [toString()](#toString--) | نمایش رشته‌ای برمی‌گرداند. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

یک شی FontData جدید با نام قلم مشخص‌شده ایجاد می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | نام قلم. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

نام قلم را برمی‌گرداند. خواندنی/قابل‌نوشتن String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

نام قلم را برمی‌گرداند و مرجع تم را با قلم واقعی استفاده‌شده جایگزین می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | تم‌ای که از آن باید نام قلم تم‌دار گرفته شود. تأمین مقدار صحیح به عهدهٔ فراخواننده است. ببینید [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returns:**
java.lang.String - نام قلم.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا دو نمونه FontData برابر هستند یا خیر.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | شی FontData که با شی FontData فعلی مقایسه می‌شود. |

**Returns:**
boolean - **true** اگر FontData مشخص‌شده با FontData فعلی برابر باشد؛ در غیر این صورت **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای نوعی خاص عمل می‌کند و برای الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است.

**Returns:**
int - کد هش FontData.
### toString() {#toString--}
```
public String toString()
```

نمایش رشته‌ای را برمی‌گرداند.

**Returns:**
java.lang.String - نمایش رشته‌ای.