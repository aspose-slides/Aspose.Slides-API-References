---
title: IMasterTheme
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
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

| متد | توضیح |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | مجموعه‌ای از طرح‌های رنگی اضافی را بر می‌گرداند. |
| [getName()](#getName--) | نام یک تم را بر می‌گرداند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک تم را بر می‌گرداند. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

مجموعه‌ای از طرح‌های رنگی اضافی را بر می‌گرداند. این طرح‌ها بر ظاهر ارائه تأثیری ندارند و می‌توانند به‌عنوان طرح رنگ اصلی برای یک اسلاید انتخاب شوند. فقط خواندنی [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**بازگشت:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```java
public abstract String getName()
```

نام یک تم را بر می‌گرداند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام یک تم را بر می‌گرداند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |