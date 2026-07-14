---
title: HtmlExternalResolver
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شیء callback مورد استفاده توسط روتین واردات HTML برای به‌دست‌آوردن اشیاء اشاره‌شده مانند تصاویر.
type: docs
url: /fa/com.aspose.slides/htmlexternalresolver/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

شیء callback مورد استفاده توسط روتین واردات HTML برای به‌دست‌آوردن اشیاء اشاره‌شده مانند تصاویر.

--------------------

استفاده از این resolver می‌تواند منجر به یک آسیب‌پذیری شود هنگامی که فایل HTML ارائه‌شده توسط مشتری باعث می‌شود نرم‌افزار سرور فایل‌های محلی یا شبکه‌ای را به‌دست‌آورد. با احتیاط استفاده کنید. توصیه می‌شود که HtmlExternalResolver را به‌طور کامل مشخص نکنید (فقط اشیاء تعبیه‌شده خوانده می‌شوند) یا زیرکلاسی ایجاد کنید که بررسی کند آیا URI مشخص‌شده معتبر است یا خیر.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | URI مطلق را از URI پایه و نسبی حل می‌کند. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | یک URI را به شیئی که منبع واقعی را شامل می‌شود، نگاشت می‌کند. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


URI مطلق را از URI پایه و نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | java.lang.String | URI پایهٔ اشیاء پیوندی |
| relativeUri | java.lang.String | URI نسبی به شیء پیوندخورده. |

**مقدار بازگشتی:**
java.lang.String - URI مطلق یا null اگر URI نسبی قابل حل نباشد.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


یک URI را به شیئی که منبع واقعی را شامل می‌شود، نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق به شیء. |

**مقدار بازگشتی:**
java.io.InputStream - یک شیء InputStream یا null اگر منبع قابل جریان‌دهی نباشد.