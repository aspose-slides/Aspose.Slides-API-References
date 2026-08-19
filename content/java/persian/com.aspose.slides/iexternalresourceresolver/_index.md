---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /fa/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

رابط callback که برای حل منابع خارجی هنگام وارد کردن اسناد Html و Svg استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | یک URI را به شیئی که حاوی منبع واقعی است نگاشت می‌کند. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | java.lang.String | URI پایهٔ اشیای پیونددهنده |
| relativeUri | java.lang.String | URI نسبی به شیء پیوند داده شده. |

**بازگشت:**
java.lang.String - URI مطلق یا null اگر URI نسبی قابل حل نباشد.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

یک URI را به شیئی که حاوی منبع واقعی است نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق به شیء. |

**بازگشت:**
java.io.InputStream - یک شی InputStream یا null اگر منبع قابل پخش نباشد.