---
title: HtmlExternalResolver
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء Callback که توسط روتین وارد کردن HTML برای دریافت اشیاء ارجاع‌شده مانند تصاویر استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/htmlexternalresolver/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

شیء Callback که توسط روتین وارد کردن HTML برای دریافت اشیاء ارجاع‌شده مانند تصاویر استفاده می‌شود.

--------------------

استفاده از این resolver می‌تواند یک آسیب‌پذیری ایجاد کند وقتی فایلی HTML که توسط مشتری فراهم شده است، باعث می‌شود نرم‌افزار سرور فایل‌های محلی یا شبکه‌ای را به دست آورد. با احتیاط استفاده کنید. توصیه می‌شود که به‌طور کامل HtmlExternalResolver را مشخص نکنید (فقط اشیاء تعبیه‌شده خوانده می‌شوند) یا یک زیرکلاس بسازید که بررسی کند آیا URI مشخص شده معتبر است یا خیر.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | یک URI را به شیئی که منبع واقعی را شامل می‌شود نگاشت می‌کند. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | java.lang.String | URI پایهٔ اشیاء پیوندی |
| relativeUri | java.lang.String | URI نسبی به شیء پیوند داده شده. |

**بازگشت:**
java.lang.String - URI مطلق یا null اگر URI نسبی قابل حل نباشد.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


یک URI را به شیئی که منبع واقعی را شامل می‌شود نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق به شیء. |

**بازگشت:**
java.io.InputStream - یک شیء InputStream یا null اگر منبع قابل جریان‌سازی نباشد.