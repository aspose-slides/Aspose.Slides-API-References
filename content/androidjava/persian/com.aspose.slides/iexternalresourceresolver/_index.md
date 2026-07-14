---
title: IExternalResourceResolver
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: رابط بازگشتی استفاده شده برای حل منابع خارجی هنگام وارد کردن اسناد Html Svg.
type: docs
url: /fa/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

رابط بازگشتی استفاده شده برای حل منابع خارجی هنگام وارد کردن اسناد Html، Svg.

## متدها

| متد | توضیح |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | آدرس مطلق را از URI پایه و URI نسبی حل می‌کند. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | یک URI را به شیئی که شامل منبع واقعی است نگاشت می‌کند. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

آدرس مطلق را از URI پایه و URI نسبی حل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | java.lang.String | URI پایه اشیای لینک دهنده |
| relativeUri | java.lang.String | URI نسبی به شیء لینک شده. |

**بازگشت:**
java.lang.String - آدرس مطلق یا null اگر URI نسبی قابل حل نباشد.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

یک URI را به شیئی که شامل منبع واقعی است نگاشت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | java.lang.String | آدرس URI مطلق به شیء. |

**بازگشت:**
java.io.InputStream - یک شیء InputStream یا null اگر منبع قابل استریم نباشد.