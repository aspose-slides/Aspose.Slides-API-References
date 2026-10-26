---
title: IMasterTheme
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک تم اصلی است.
type: docs
url: /fa/com.aspose.slides/imastertheme/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

نمایانگر یک تم اصلی است.
## متدها

| Method | Description |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | مجموعه‌ای از طرح‌های رنگی اضافه را باز می‌گرداند. |
| [getName()](#getName--) | نام یک تم را باز می‌گرداند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک تم را باز می‌گرداند. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


مجموعه‌ای از طرح‌های رنگی اضافه را باز می‌گرداند. این طرح‌ها بر ظاهر ارائه تأثیر نمی‌گذارند و می‌توانند به‌عنوان طرح رنگ اصلی برای یک اسلاید انتخاب شوند. فقط-خواندنی [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**بازگشت:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


نام یک تم را باز می‌گرداند. قابل خواندن/قابل نوشتن String.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


نام یک تم را باز می‌گرداند. قابل خواندن/قابل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |