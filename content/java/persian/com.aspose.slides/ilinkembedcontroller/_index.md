---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /fa/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

رابط فراخوانی که برای تعیین نحوه پردازش شیء هنگام ذخیره‌سازی استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | محل ذخیره‌سازی شیء را تعیین می‌کند. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | یک URL به شیء خارجی را برمی‌گرداند. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | شیء خارجی را ذخیره می‌کند. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


محل ذخیره‌سازی شیء را تعیین می‌کند. این متد یک بار برای هر شناسه شیء فراخوانی می‌شود. این تضمین نمی‌شود که دو شیء با داده‌های یکسان، semanticName و contentType یکسان وجود نداشته باشند، اما شناسه‌های متفاوت داشته باشند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسه شیء. این شناسه در تمام عملیات ذخیره‌سازی منحصربه‌فرد است. |
| entityData | byte[] | داده‌های باینری شیء. این پارامتر می‌تواند null باشد، اگر داده‌های باینری شیء هنوز تولید نشده باشد. |
| semanticName | java.lang.String | متن کوتاهی که معنای شیء را توصیف می‌کند. کنترلر ممکن است از این متن به عنوان بخشی از نام شیء خارجی استفاده کند، اما تضمین یکتایی نام‌ها و صرفاً شامل کاراکترهای مجاز بر عهدهٔ دیسپاچر است. |
| contentType | java.lang.String | نوع MIME شیء. |
| recomendedExtension | java.lang.String | پسوند نام فایل، که برای این نوع MIME توصیه می‌شود. |

**بازگشت:**
int - تصمیم
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


یک URL به شیء خارجی را برمی‌گرداند. این متد همواره اگر \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) مقدار [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) را بازگرداند فراخوانی می‌شود و ممکن است اگر همان متد مقدار [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) را بازگرداند، اما جاسازی ممکن نباشد، فراخوانی شود. می‌تواند برای همان شناسه شیء چندین بار فراخوانی شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسه شیء. این شناسه در تمام عملیات ذخیره‌سازی منحصربه‌فرد است. |
| referrer | int | شناسهٔ شیء ارجاع‌دهنده یا 0، اگر شیء توسط سند ریشه ارجاع داده شده باشد. می‌تواند برای تولید لینک نسبی استفاده شود. |

**بازگشت:**
java.lang.String - URL شیء خارجی یا null اگر این شیء باید نادیده گرفته شود.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


شیء خارجی را ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int | شناسه شیء. این شناسه در تمام عملیات ذخیره‌سازی منحصربه‌فرد است. |
| entityData | byte[] | داده‌های باینری شیء. این پارامتر نمی‌تواند null باشد. |