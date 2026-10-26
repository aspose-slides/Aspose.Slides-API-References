---
title: ExternalResourceResolver
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاسی که برای حل منابع خارجی هنگام وارد کردن اسناد Html و Svg استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)  
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

کلاسی که برای رفع منابع خارجی هنگام وارد کردن اسناد Html و Svg استفاده می‌شود.

--------------------

استفاده از این حل‌کننده می‌تواند باعث بوجود آمدن آسیب‌پذیری شود؛ وقتی فایلی HTML یا SVG توسط مشتری ارائه می‌شود، نرم‌افزار سرور می‌تواند به فایل‌های محلی یا شبکه‌ای دسترسی پیدا کند. با احتیاط استفاده کنید. توصیه می‌شود که ExternalResourceResolver را به‌طور کلی مشخص نکنید (فقط اشیاء Embedded خوانده می‌شوند) یا یک زیرکلاس ایجاد کنید که صحت URI مشخص‌شده را بررسی نماید.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

URI مطلق را از URIهای پایه و نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**بازگرداندن:**  
java.lang.String - URI مطلق یا null اگر URI نسبی قابل حل نباشد.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

یک URI را به شیئی که شامل منبع واقعی است نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**بازگرداندن:**  
java.io.InputStream - یک شیء InputStream یا null اگر منبع قابل استریم نباشد.