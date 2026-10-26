---
title: ExternalResourceResolver
second_title: Aspose.Slides برای مرجع API جاوا
description: کلاس Callback که برای حل منابع خارجی هنگام وارد کردن اسناد Html و Svg استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/externalresourceresolver/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

کلاس Callback که برای حل منابع خارجی هنگام وارد کردن اسناد Html و Svg استفاده می‌شود.

--------------------

استفاده از این حل‌کننده می‌تواند باعث ایجاد آسیب‌پذیری شود؛ زمانی که فایل HTML یا SVG ارائه‌شده توسط کاربر، نرم‌ افزار سرور را وادار به دسترسی به فایل‌های محلی یا شبکه‌ای می‌کند. با احتیاط استفاده کنید. توصیه می‌شود که ExternalResourceResolver را اصلاً مشخص نکنید (فقط اشیاء تعبیه‌شده خوانده می‌شوند) یا زیرکلاسی ایجاد کنید که بررسی کند آیا URI مشخص شده معتبر است یا خیر.
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | URI مطلق را از URI‌های پایه و نسبی حل می‌کند. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | یک URI را به شیء حاوی منبع واقعی نگاشت می‌کند. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


URI مطلق را از URI‌های پایه و نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | |
| baseUri | java.lang.String | URI پایهٔ اشیاء پیوندی |
| relativeUri | java.lang.String | URI نسبی به شیء پیوندی. |

**بازگرداندن:**
java.lang.String - URI مطلق یا null اگر URI نسبی قابل حل نباشد.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


یک URI را به شیء حاوی منبع واقعی نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | |
| absoluteUri | java.lang.String | URI مطلق به شیء. |

**بازگرداندن:**
java.io.InputStream - یک شیء InputStream یا null اگر منبع قابل استریم نباشد.