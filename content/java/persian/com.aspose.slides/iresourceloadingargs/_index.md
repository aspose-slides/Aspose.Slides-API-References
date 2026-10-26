---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: رابط برای آرگومان‌های بارگذاری منبع خارجی.
type: docs
url: /fa/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface for external resource loading arguments.
## متدها

| متد | توضیح |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Original URI of the resource as specified in imported presentation. |
| [getUri()](#getUri--) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Sets user provided data of the resource which used if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI اصلی منبع همان‌گونه که در ارائه وارد شده مشخص شده است.

**بازمی‌گرداند:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI منبعی که در صورت بازگشت [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) مقدار [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) برای دانلود استفاده می‌شود. در ابتدا به URI اصلی منبع تنظیم می‌شود، اما می‌تواند به هر مقدار دیگری تغییر یابد.

**بازمی‌گرداند:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI منبعی که در صورت بازگشت [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) مقدار [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) برای دانلود استفاده می‌شود. در ابتدا به URI اصلی منبع تنظیم می‌شود، اما می‌تواند به هر مقدار دیگری تغییر یابد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


داده‌های ارائه شده توسط کاربر برای منبع را تنظیم می‌کند که در صورت بازگرداندن [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) مقدار [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های ارائه شده از منبع byte[] |