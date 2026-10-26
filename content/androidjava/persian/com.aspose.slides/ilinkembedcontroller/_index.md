---
title: ILinkEmbedController
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: رابط بازخوانی که برای تعیین نحوه پردازش شیء هنگام ذخیره‌سازی استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

رابط بازخوانی که برای تعیین نحوه پردازش شیء هنگام ذخیره‌سازی استفاده می‌شود.

## متدها

| متد | توضیح |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | محل ذخیره‌سازی شیء را تعیین می‌کند. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | یک URL برای شیء خارجی برمی‌گرداند. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | شیء خارجی را ذخیره می‌کند. |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

محل ذخیره‌سازی شیء را تعیین می‌کند. این متد برای هر شناسهٔ شیء یک بار فراخوانی می‌شود. تضمین نمی‌شود که دو شیء با داده، semanticName و contentType یکسان ولی شناسه متفاوت وجود نداشته باشند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسهٔ شیء. این شناسه در کل عملیات ذخیره‌سازی یکتا است. |
| entityData | byte[] | دادهٔ باینری شیء. این پارامتر می‌تواند null باشد، اگر دادهٔ باینری شیء هنوز تولید نشده باشد. |
| semanticName | java.lang.String | متن کوتاهی که معنای شیء را توصیف می‌کند. کنترلر ممکن است از این به عنوان بخشی از نام شیء خارجی استفاده کند، اما اطمینان از یکتا بودن نام‌ها و داشتن تنها کاراکترهای مجاز بر عهدهٔ ارسال‌کننده است. |
| contentType | java.lang.String | نوع MIME شیء. |
| recomendedExtension | java.lang.String | پسوند نام فایل، که برای این نوع MIME توصیه می‌شود. |

**بازگرداندن:**
int - تصمیم

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

یک URL برای شیء خارجی برمی‌گرداند. این متد همیشه زمانی فراخوانی می‌شود که \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) مقدار [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) را برگرداند و ممکن است اگر همان متد مقدار [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) را برگرداند اما جاسازی ممکن نباشد، فراخوانی شود. می‌تواند برای یک شناسهٔ شیء چندین بار فراخوانی شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسهٔ شیء. این شناسه در کل عملیات ذخیره‌سازی یکتا است. |
| referrer | int | شناسهٔ شیء مرجع یا 0، اگر شیء توسط سند ریشه ارجاع داده شود. می‌تواند برای تولید لینک نسبی استفاده شود. |

**بازگرداندن:**
java.lang.String - URL شیء خارجی یا null اگر این شیء باید نادیده گرفته شود.

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

شیء خارجی را ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسهٔ شیء. این شناسه در کل عملیات ذخیره‌سازی یکتا است. |
| entityData | byte[] | دادهٔ باینری شیء. این پارامتر نمی‌تواند null باشد. |